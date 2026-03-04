# Google Calendar Birthday Automation

Efficiently automate birthday reminders from your Google Calendar directly to WhatsApp using n8n and Evolution API.

[English](#english) | [Português](#português)

---

## English <a name="english"></a>

This repository provides a production-ready n8n workflow designed to fetch daily birthday events from your Google Calendar and send personalized reminders via WhatsApp.

### Workflow Preview
![n8n Workflow Preview](assets/workflow.png)

### Key Features
*   Daily Automation: Triggered automatically every day at 06:00 AM.
*   Intelligent Filtering: Specifically targets only full-day birthday events.
*   Personalized Messaging: Sends a direct WhatsApp message via Evolution API.
*   Privacy First: Sanitized workflow ready for your own credentials.

### Setup Instructions
1.  **Import**: Download the `workflow_sanitized.json` file and import it into your n8n instance.
2.  **Authentication**: Configure your Google Calendar ecosystem in the **Google Calendar (V2)** node.
3.  **Customization**: Locate the placeholders **"Insira sua chave aqui"** and replace them with:
    *   **Calendar ID**: Your specific Google Calendar ID.
    *   **Instance Name**: Your Evolution API instance identifier.
    *   **Target Contact**: The phone number (`remoteJid`) to receive the notification.
4.  **Activation**: Ensure your Evolution API endpoint is active and tested.

---

## Português <a name="português"></a>

Este repositório contém um fluxo n8n completo para automatizar o envio de lembretes de aniversário do Google Calendar para o seu WhatsApp através da Evolution API.

### Visualização do Fluxo
![Visualização do Fluxo n8n](assets/workflow.png)

### Funcionalidades Principais
*   Automação Diária: Gatilho automático disparado todos os dias às 06:00.
*   Filtro Inteligente: Identifica exclusivamente eventos de aniversário do dia.
*   Mensagens Diretas: Envio via Evolution API para o seu WhatsApp.
*   Privacidade: Fluxo sanitizado, pronto para receber suas próprias credenciais.

### Guia de Configuração
1.  **Importação**: Baixe o arquivo `workflow_sanitized.json` e importe-o no seu n8n.
2.  **Autenticação**: Configure o node **Google Calendar (V2)** com sua conta Google.
3.  **Ajustes**: Encontre os campos marcados como **"Insira sua chave aqui"** e substitua por:
    *   **ID do Calendário**: O identificador do seu calendário Google.
    *   **Nome da Instância**: O nome da sua instância na Evolution API.
    *   **Contato de Destino**: O número de telefone (`remoteJid`) que receberá o aviso.
4.  **Ativação**: Verifique se a sua Evolution API está respondendo corretamente.
