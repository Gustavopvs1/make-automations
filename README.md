# ⚙️ Make Automations

A collection of automation flows built with [Make (ex Integromat)](https://www.make.com) for a real logistics operation. Each scenario solves a specific internal process problem.

> Screenshots show the general structure of each scenario. Sensitive data, credentials, and internal names have been removed.

---

## Flows

| Automation | Tools | Description |
|---|---|---|
| [🤖 Telegram AI Support Bot](./chatbot-sistemas-telegram/) | Telegram · Make AI Agents · Outlook · Google Sheets · HTTP | Internal support bot with AI, routing, and escalation |
| [📧 Email-to-PDF Processor](./automatizacion-correos-pdf/) | Outlook · Text Parser · Custom JS · Gmail | Detects emails by subject keyword, converts body to PDF, forwards them |
| [📦 Odoo Order Sync](./sync-odoo-excel/) | Google Sheets · Odoo API · HTTP | Creates purchase or sales orders in Odoo from an Excel file based on stock availability |

---

## Stack

![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)
![JavaScript](https://img.shields.io/badge/Custom_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)