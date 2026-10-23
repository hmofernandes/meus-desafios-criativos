Atue como um especialista em N8N.

Crie uma automação para gerir pedidos de contacto recebidos por e-mail.

Público: Pequenas empresas e equipas de atendimento ao cliente.

Ferramentas envolvidas: Gmail e Google Sheets.

Fluxo:

Detetar a receção de um novo e-mail no Gmail.
Verificar se o e-mail contém um pedido de contacto com nome, endereço de e-mail e mensagem.
Registar os dados do pedido numa nova linha de uma folha do Google Sheets, incluindo a data de receção e o estado "Pendente".
Se os dados estiverem completos, enviar uma notificação por e-mail à equipa de atendimento, com o resumo do pedido.
Se faltarem dados essenciais, registar o pedido com o estado "Incompleto", quando possível, sem enviar a notificação habitual.
Regras:

Processar apenas e-mails recebidos na caixa de entrada que correspondam a pedidos de contacto.
Ignorar mensagens de spam e e-mails enviados pela própria empresa.
Não registar o mesmo e-mail mais do que uma vez, utilizando o identificador único da mensagem.
Se ocorrer um erro ao guardar os dados na folha de cálculo, não enviar a notificação de novo pedido.
Guardar a data de receção para facilitar o acompanhamento dos pedidos.
Explique quais os nós do N8N que devem ser utilizados e a lógica de funcionamento do workflow.