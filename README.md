<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" />

# 🎫 Open Event Website Generator

### Plataforma Open Source para generar sitios web de eventos y conferencias 🚀

<p align="center">
  <b>Open Event Website Generator</b> permite crear automáticamente páginas web dinámicas para eventos, conferencias y meetups utilizando archivos JSON y recursos multimedia.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-API-black?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.IO-Realtime-010101?style=for-the-badge&logo=socket.io&logoColor=white" />
  <img src="https://img.shields.io/badge/SASS-Styling-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
  <img src="https://img.shields.io/badge/Open_Source-FOSSASIA-blue?style=for-the-badge" />
</p>

</div>

---

# 📖 Descripción

**Open Event Website Generator** es una plataforma web desarrollada por **FOSSASIA** que automatiza la creación de sitios web para eventos mediante plantillas dinámicas y archivos estructurados en formato JSON.

El sistema permite:

- Generar páginas web completas para eventos
- Subir archivos comprimidos con información del evento
- Desplegar sitios automáticamente
- Integrarse mediante API REST
- Publicar eventos en GitHub Pages o servidores externos

Está diseñado para conferencias, congresos, meetups, hackathons y eventos tecnológicos.

---

# ✨ Características Principales

## 🎟️ Generador Automático de Eventos

- Generación completa de sitios web dinámicos
- Soporte para múltiples temas visuales
- Exportación lista para producción

## 📦 Importación de Datos

- Soporte para archivos JSON
- Manejo de imágenes y multimedia
- Compatibilidad con Open Event Format

## 🌐 API REST

- Generación mediante endpoints REST
- Automatización de procesos
- Integración con plataformas externas

## ☁️ Despliegue Automático

- GitHub Pages
- AWS
- Google Cloud
- Digital Ocean
- FTP Deploy

## 📊 Gestión de Contenido

- Speakers
- Tracks
- Sponsors
- Sessions
- Schedule
- Locations
- Code of Conduct

## 🧪 Testing Automatizado

- Selenium WebDriver
- Testing de páginas generadas
- Validación automática de eventos

---

# 🏗️ Arquitectura del Proyecto

```bash
open-event-wsgen/
├── src/
│   ├── backend/          # Lógica del generador
│   ├── selenium/         # Testing automatizado
│   ├── www/              # Frontend del generador
│   └── app.js            # Servidor Express principal
│
├── docs/                 # Documentación
├── config.json           # Configuración global
├── test/                 # Tests
└── package.json
```

---

# ⚙️ Tecnologías Utilizadas

| Tecnología | Uso |
|---|---|
| Node.js | Backend principal |
| Express.js | API y servidor |
| Socket.IO | Comunicación en tiempo real |
| Handlebars | Motor de plantillas |
| SASS | Estilos avanzados |
| Selenium | Testing automatizado |
| AWS S3 | Almacenamiento |
| GitHub API | Deploy automático |

---

# 🧩 Componentes del Sistema

## 🌍 Frontend Generator

Interfaz web para:

- Subir archivos ZIP
- Configurar eventos
- Seleccionar temas
- Generar páginas web

## ⚡ Backend Generator

Motor encargado de:

- Procesar JSON
- Renderizar templates
- Generar HTML
- Optimizar assets
- Desplegar sitios

## 🧪 Selenium Testing

Sistema automatizado para validar:

- Speakers pages
- Schedule pages
- Sessions
- Tracks
- Rooms
- Generator UI

---

# 📄 Plantillas Disponibles

El generador utiliza plantillas Handlebars:

| Plantilla | Descripción |
|---|---|
| `event.hbs` | Página principal |
| `schedule.hbs` | Agenda del evento |
| `speakers.hbs` | Speakers |
| `rooms.hbs` | Salas |
| `session.hbs` | Sesiones |
| `CoC.hbs` | Código de conducta |

---

# 🚀 Instalación

## 📋 Requisitos

- Node.js
- npm
- Git

---

## 🔧 Clonar el proyecto

```bash
git clone https://github.com/fossasia/open-event-wsgen.git
cd open-event-wsgen
```

---

## 📦 Instalar dependencias

```bash
npm install
```

---

## ▶️ Ejecutar el proyecto

```bash
npm start
```

Servidor disponible en:

```bash
http://localhost:5000
```

---

# 🌐 Uso del Generador

## 📁 Subir Evento

El usuario debe subir un archivo ZIP que contenga:

- event.json
- speakers.json
- sessions.json
- sponsors.json
- tracks.json
- locations.json

---

## ⚙️ Configurar

Seleccionar:

- Tema visual
- API version
- Session style
- Deployment mode

---

## 🎉 Generar Sitio

Opciones disponibles:

- Descargar ZIP
- Deploy automático
- Publicar en GitHub Pages

---

# 🔌 API REST

## Endpoint principal

```http
POST /generate
```

## Parámetros

| Parámetro | Descripción |
|---|---|
| name | Nombre del sitio |
| email | Correo del usuario |
| datasource | Fuente de datos |
| apiendpoint | Endpoint externo |

---

# ☁️ Integraciones

## AWS S3

- Almacenamiento temporal
- Descargas automáticas

## GitHub Pages

- Deploy automático
- Publicación instantánea

## SMTP / SendGrid

- Notificaciones por correo
- Alertas de generación

---

# 🧪 Testing

## Ejecutar tests

```bash
npm test
```

## Ejecutar test específico

```bash
npx mocha -b test/generatorAndSchedule.js
```

---

# 📊 Características Técnicas

- Arquitectura modular
- Plantillas reutilizables
- Generación dinámica
- Optimización automática
- Multi-event support
- Renderizado server-side
- Compatible con Open Event Format

---

# 🔐 Seguridad

- Validación de uploads
- Sanitización de datos
- Manejo seguro de APIs
- Variables de entorno protegidas

---

# 🌍 Open Source

Proyecto desarrollado como parte de:

## ❤️ FOSSASIA Open Event Project

Plataforma open source enfocada en:

- Gestión de conferencias
- Automatización de eventos
- Ecosistema de herramientas colaborativas

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas.

## Flujo recomendado

```bash
git checkout development
git checkout -b feature/nueva-funcionalidad
```

---

# 📜 Licencia

Proyecto distribuido bajo licencia Open Source por **FOSSASIA**.

---

# 👨‍💻 Fundador del Proyecto

<div align="center">

## FOSSASIA Open Event Team

Plataforma colaborativa enfocada en herramientas open source para eventos, conferencias y comunidades tecnológicas.

</div>
## LICENSE

OpenEvent Website Generator - A webapp and it's generator, written as part of the FOSSASIA Open Event project. The Open Event project aims to make server and client software required for hosting events/conferences easy to build and configure. Copyright (C) 2016, FOSSASIA. This program is free software: you can redistribute it and/or modify it. Please refer to the license document for more information.
