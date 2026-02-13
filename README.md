# 📬 Airtable → Email Automation (n8n + OpenAI)

Workflow de automatización desarrollado con **n8n** que detecta nuevos pedidos en Airtable, genera automáticamente un resumen utilizando OpenAI y envía notificaciones por correo electrónico mediante Gmail.

## 🚀 Qué hace

- Detecta nuevos pedidos en Airtable automáticamente.
- Procesa la información del pedido.
- Genera un email profesional usando IA.
- Envía el correo automáticamente al equipo.

Todo el proceso funciona sin intervención manual.

## ⚙️ Stack Tecnológico

- n8n (workflow automation)
- Airtable API
- OpenAI API
- Gmail API

## 🔄 Flujo del sistema

Airtable Trigger → OpenAI (generación del email) → Gmail (envío automático)

## 📊 Datos procesados

El workflow utiliza los siguientes campos del pedido:
- order number
- costumer
- product
- quantity
- price
- date
- status

## 🧠 Objetivo del proyecto

Automatizar notificaciones internas de pedidos y demostrar la integración de herramientas no-code con inteligencia artificial dentro de un flujo real de trabajo.

## 🛠️ Uso

Importar el archivo JSON del workflow en n8n y configurar las credenciales de Airtable, OpenAI y Gmail.

## 🔒 Seguridad

No incluir API keys ni credenciales en el repositorio. Utilizar el sistema seguro de credenciales de n8n.

## 📄 Licencia

MIT
