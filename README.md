# Google Calendar Birthday Automation

Este fluxo do n8n automatiza o envio de lembretes de aniversários do Google Calendar para o seu WhatsApp através da Evolution API.

## Funcionalidades
- Gatilho diário às 06:00.
- Busca eventos do dia no Google Calendar.
- Filtra eventos de aniversário.
- Envia uma mensagem personalizada via Evolution API.

## Configuração
1. Importe o arquivo `workflow.json` no seu n8n.
2. Substitua os campos marcados como **"Insira sua chave aqui"**:
   - No node **Google Calendar (V2)**: O ID do calendário e as credenciais OAuth2.
   - No node **Evolution API Out**: O nome da instância e o número de destino (`remoteJid`).
3. Certifique-se de que a Evolution API está configurada corretamente no seu n8n.
