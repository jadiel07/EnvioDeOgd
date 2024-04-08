# Envio Automatizado de E-mails

Este é um aplicativo Python desenvolvido para automatizar o processo de envio de e-mails com base em uma planilha do Excel. Ele permite enviar e-mails para destinatários associados a meses específicos de forma rápida e eficiente.

## Funcionalidades

- Analisa uma planilha do Excel em busca de destinatários associados a meses específicos.
- Envia e-mails para os destinatários encontrados na planilha.
- Economiza tempo automatizando o processo de envio de e-mails.

## Como Usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Instale as dependências necessárias executando `pip install -r requirements.txt`.
3. Execute o aplicativo Python `envio_emails.py`.
4. Selecione o mês desejado para enviar os e-mails.

## Estrutura da Planilha

- A planilha deve conter colunas numeradas de 1 a 12, representando os meses do ano.
- Um "X" na célula de um mês indica que o e-mail associado a essa linha deve ser enviado durante esse mês.
- O corpo do e-mail é obtido a partir de uma coluna específica (por exemplo, coluna 4) e abaixo da linha correspondente.

## Autor

Este aplicativo foi desenvolvido por [Jadiel Santos de Souza] e está disponível sob a licença .
