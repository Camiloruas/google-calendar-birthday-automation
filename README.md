# Google Calendar Birthday Automation / Automação de Aniversários do Google Calendar

[English](#english) | [Português](#português)

---

## English

This n8n workflow automates sending birthday reminders from Google Calendar to your WhatsApp via Evolution API.

### Workflow Preview
![n8n Workflow](assets/workflow.png)

### Key Features
- Daily trigger at 06:00 AM.
- Fetches daily events from Google Calendar.
- Filters for birthday events.
- Sends a personalized message via Evolution API.

### Setup Instructions
1. Import the `workflow.json` file into your n8n instance.
2. Replace the fields marked as **"Insira sua chave aqui"**:
   - In the **Google Calendar (V2)** node: Calendar ID and OAuth2 credentials.
   - In the **Evolution API Out** node: Instance name and target phone number (`remoteJid`).
3. Ensure the Evolution API is correctly configured in your n8n environment.

---

## Português

Este fluxo do n8n automatiza o envio de lembretes de aniversários do Google Calendar para o seu WhatsApp através da Evolution API.

### Visualização do Fluxo
![Fluxo n8n](assets/workflow.png)

### Funcionalidades
- Gatilho diário às 06:00.
- Busca eventos do dia no Google Calendar.
- Filtra eventos de aniversário.
- Envia uma mensagem personalizada via Evolution API.

### Configuração
1. Importe o arquivo `workflow.json` no seu n8n.
2. Substitua os campos marcados como **"Insira sua chave aqui"**:
   - No node **Google Calendar (V2)**: O ID do calendário e as credenciais OAuth2.
   - No node **Evolution API Out**: O nome da instância e o número de destino (`remoteJid`).
3. Certifique-se de que a Evolution API está configurada corretamente no seu n8n.
