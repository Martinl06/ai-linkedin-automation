# ai-linkedin-automation

AI LinkedIn Automation con n8n

Proyecto de automatización desarrollado con n8n y OpenAI Platform para generar contenido automáticamente para LinkedIn a partir de noticias de tecnología.

🚀 Descripción del Proyecto

Este workflow automatiza el proceso de:

obtener noticias tech desde RSS feeds,
generar publicaciones profesionales usando IA,
guardar el contenido generado en Google Sheets,
y enviar una notificación por email con los datos generados.

El objetivo de este proyecto fue aprender:

automatización de workflows,
integración de APIs,
generación de contenido con IA,
y orquestación de datos con n8n.

Arquitectura del Workflow

Schedule Trigger
        ↓
RSS Feed Read
        ↓
Limit
        ↓
OpenAI
        ↓
Google Sheets
        ↓
Email Notification

🔥 Funcionalidades

Lectura automática de noticias tech desde RSS
Procesamiento de artículos automáticamente
Generación de posts para LinkedIn usando IA
Almacenamiento automático en Google Sheets
Envío de emails con el contenido generado
Workflow completamente automatizado con n8n

🛠 Tecnologías Utilizadas
n8n
OpenAI Platform
Google Sheets
RSS Feeds
Integración Email
APIs REST
Automatización de workflows

📌 Caso de Uso

Este workflow puede adaptarse para:

automatización de contenido,
marketing automation,
social media management,
newsletters automáticos,
generación de contenido con IA,
pipelines automatizados.
📷 Capturas

📂 Archivos Incluidos

workflow.json
README.md
screenshots/

🧠 Aprendizajes

Durante este proyecto practiqué:

integración de APIs,
manejo de JSON,
prompt engineering,
automatización de procesos,
diseño de workflows,
generación de contenido con IA.

🎯 Próximas Mejoras
Publicación automática en LinkedIn
Sistema de aprobación manual
Generación de imágenes con IA
Dashboard de métricas
Publicación multi plataforma
Sistema de scheduling avanzado

👨‍💻 Autor

Proyecto desarrollado como práctica de automatización e inteligencia artificial utilizando n8n.
