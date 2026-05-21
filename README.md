<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" />

# 🎫 Open Event Website Generator

### Plataforma Open Source para generar sitios web de eventos y conferencias 🚀

<p align="center">
  <b>Open Event Website Generator</b> permite crear automáticamente páginas web dinámicas para eventos, conferencias y meetups utilizando archivos JSON y recursos multimedia.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Express.js-API-black?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/Socket.IO-Realtime-010101?style=for-the-badge&logo=socket.io&logoColor=white">
  <img src="https://img.shields.io/badge/Handlebars-Templates-f0772b?style=for-the-badge">
  <img src="https://img.shields.io/badge/SASS-Styling-CC6699?style=for-the-badge&logo=sass&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-api-rest">API</a>
</p>

</div>

---

# 🎫 Acerca del proyecto

**Open Event Website Generator** es una plataforma open source desarrollada para automatizar la creación de sitios web para eventos, conferencias, hackathons y meetups utilizando archivos JSON y recursos multimedia.

El sistema permite:

- 🌐 Generar sitios web dinámicos para eventos
- 📦 Importar datos mediante archivos ZIP
- ⚡ Crear páginas automáticamente
- ☁️ Desplegar eventos en GitHub Pages
- 🔌 Integrarse mediante API REST
- 📊 Gestionar speakers, tracks y schedules

La plataforma forma parte del ecosistema **FOSSASIA Open Event**.

---

# ✨ Características

## 🎟️ Generador de eventos

- 🌐 Generación automática de sitios web
- ⚡ Renderizado dinámico de contenido
- 📱 Diseño responsive
- 🎨 Soporte para temas visuales
- 🧩 Plantillas reutilizables

---

## 📦 Gestión de contenido

- 👨‍🏫 Speakers
- 🗓️ Schedules
- 🎤 Sessions
- 🏢 Rooms
- 🧭 Tracks
- 🤝 Sponsors
- 📍 Locations

---

## ☁️ Deploy automático

- 🚀 GitHub Pages
- ☁️ AWS
- 🌍 Digital Ocean
- 🖥️ Google Cloud
- 📡 FTP Deploy

---

## 🔌 API REST

- ⚡ Generación vía API
- 📦 Upload de eventos
- 🌐 Integraciones externas
- 🔄 Automatización de procesos

---

## 🧪 Testing automatizado

- ✅ Selenium WebDriver
- ⚡ Testing de páginas generadas
- 📊 Validación automática
- 🔍 Verificación de eventos

---

# 👨‍💻 Componentes del sistema

## 🌍 Frontend Generator

Interfaz web utilizada para:

- 📤 Subir archivos ZIP
- 🎨 Elegir temas
- ⚙️ Configurar eventos
- 🚀 Generar sitios web

---

## ⚡ Backend Generator

Motor principal encargado de:

- 📦 Procesar JSON
- 🧩 Renderizar templates
- 🌐 Generar páginas HTML
- ☁️ Gestionar despliegues

---

## 🧪 Selenium Testing

Sistema de pruebas automatizadas para:

- 🎤 Speakers pages
- 📅 Schedule pages
- 🏢 Rooms
- 🧭 Tracks
- 📄 Sessions

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,js" />
</p>

- Node.js
- Express.js
- JavaScript
- REST API

---

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,sass" />
</p>

- HTML5
- CSS3
- SASS
- Responsive Design

---

## 🧩 Templates & Real Time

<p>
  <img src="https://skillicons.dev/icons?i=socketio" />
</p>

- Handlebars
- Socket.IO
- Dynamic Rendering
- Real-time generation

---

## ☁️ Cloud & Deploy

<p>
  <img src="https://skillicons.dev/icons?i=aws,github" />
</p>

- AWS S3
- GitHub Pages
- FTP Deploy
- Cloud Hosting

---

## 🧪 Testing

<p>
  <img src="https://skillicons.dev/icons?i=selenium" />
</p>

- Selenium WebDriver
- Mocha Testing
- Automated UI Testing

---

# 📂 Estructura del proyecto

```bash
open-event-wsgen/
│
├── src/
│   ├── backend/
│   ├── selenium/
│   ├── www/
│   └── app.js
│
├── docs/
├── test/
├── config.json
├── package.json
└── README.md
```

---

# 🏗️ Arquitectura del sistema

## ⚡ Flujo principal

```text
Usuario → Upload ZIP → Generator Engine → Render Templates → Deploy Website
```

---

## 🌐 Arquitectura general

```text
Frontend → Express API → Generator → Templates → Deploy
```

---

# 📄 Plantillas disponibles

| Template | Descripción |
|---|---|
| `event.hbs` | Página principal |
| `schedule.hbs` | Agenda del evento |
| `speakers.hbs` | Lista de speakers |
| `rooms.hbs` | Salas y venues |
| `session.hbs` | Sesiones individuales |
| `CoC.hbs` | Código de conducta |

---

# ⚡ Instalación

## 📋 Requisitos

- Node.js
- npm
- Git
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/fossasia/open-event-wsgen.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd open-event-wsgen
```

---

## 3️⃣ Instalar dependencias

```bash
npm install
```

---

## 4️⃣ Ejecutar servidor

```bash
npm start
```

---

## 🌐 Acceder al sistema

```bash
http://localhost:5000
```

---

# 🔌 API REST

## Endpoint principal

```http
POST /generate
```

---

## Parámetros

| Parámetro | Descripción |
|---|---|
| name | Nombre del sitio |
| email | Correo del usuario |
| datasource | Tipo de fuente |
| apiendpoint | Endpoint externo |

---

# 📊 Funcionalidades principales

## 🎟️ Event Generator

- ⚡ Generación dinámica
- 🌐 Multi-event support
- 📦 ZIP processing
- 🎨 Templates dinámicos

---

## ☁️ Deploy automático

- 🚀 GitHub Pages
- 🌍 Cloud Deploy
- 📡 FTP Integration
- 📦 ZIP Export

---

## 🧪 Testing

- 🔍 Selenium Tests
- 📊 UI Validation
- ⚡ Automated checks

---

# 🔐 Seguridad

## 🛡️ Protección del sistema

- 📦 Validación de uploads
- 🔒 Sanitización de datos
- ⚡ Variables de entorno
- ☁️ Gestión segura de APIs

---

# 📸 Vista previa

## 🌐 Open Event Generator

<div align="center">

### 🎫 Dashboard del generador
![Dashboard](https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=1200)

### 📅 Sitio web del evento
![Event](https://images.unsplash.com/photo-1511578314322-379afb476865?q=80&w=1200)

### ☁️ Deploy automático
![Deploy](https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=1200)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Desarrollo Open Source

- Arquitectura Node.js
- Renderizado dinámico
- APIs REST
- Deploy automático
- Testing automatizado
- Cloud hosting
- Gestión de eventos

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 🤖 AI Event Assistant
- 📱 Progressive Web App
- 🌐 Multi-language support
- 📊 Analytics dashboard
- 🔔 Push notifications
- ☁️ Serverless deployment

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## FOSSASIA Open Event Team

Equipo open source enfocado en plataformas modernas para gestión de eventos y conferencias 🌍

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto Open Source desarrollado bajo la comunidad **FOSSASIA** para automatización de eventos y generación de sitios web dinámicos.

---

<div align="center">

### 🎫 Open Event Website Generator — eventos inteligentes y automatizados 🚀

</div>
