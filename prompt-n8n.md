Atue como um especialista em N8N.

Crie uma automação para realizar a triagem automática de novos candidatos a vagas de emprego.

Público:
Equipe de Recursos Humanos (RH) e Departamento Financeiro.

Ferramentas envolvidas:
Typeform, Google Sheets, Nós Condicionais do N8N (If/Switch), Bloco de Código JavaScript (Função Split) e Gmail.

Fluxo:
1. Receber uma nova resposta de candidatura através do formulário do Typeform.
2. Registrar e estruturar todos os dados recolhidos em uma planilha do Google Sheets.
3. Passar os dados por um nó de decisão para checar o status e disparar e-mails dinâmicos baseados no primeiro nome do candidato.

Regras:
Se o status for 'APROVADO', usar a função split para pegar apenas o primeiro nome e enviar e-mail individual avançando para PAGAMENTO. Se for 'PENDENTE', direcionar para ANALISE_MANUAL. Se for 'NEGADO', enviar para ENCERRAMENTO. Qualquer outro valor incompleto ou incorreto deve retornar a mensagem ERRO_STATUS para o sistema.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
