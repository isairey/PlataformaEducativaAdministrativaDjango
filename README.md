<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/5968/5968705.png" />

# 🎓 We All Code Platform

### Plataforma educativa y administrativa desarrollada con Django 🚀

<p align="center">
  <b>We All Code Platform</b> es una aplicación web personalizada desarrollada con Django para gestionar múltiples áreas organizacionales, incluyendo administración, mentorías, tutores y gestión educativa mediante una arquitectura moderna basada en Docker.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Django-Backend-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-arquitectura">Arquitectura</a>
</p>

</div>

---

# 🎓 Acerca del proyecto

**We All Code Platform** es una plataforma web desarrollada con Django diseñada para administrar distintos procesos internos de una organización educativa y tecnológica.

El sistema permite gestionar:

- 👨‍🏫 Mentorías
- 👨‍👩‍👧 Gestión de guardianes
- 👨‍💼 Administración interna
- 📚 Gestión educativa
- 🔐 Autenticación de usuarios
- 🐳 Infraestructura Docker
- ⚡ Desarrollo colaborativo

La plataforma está construida bajo una arquitectura moderna basada en contenedores para facilitar el desarrollo, despliegue y mantenimiento del sistema.

---

# ✨ Características

## 🎓 Gestión educativa

- 👨‍🏫 Administración de mentores
- 👨‍🎓 Gestión de estudiantes
- 👨‍👩‍👧 Gestión de guardianes
- 📚 Organización académica
- 📊 Panel administrativo

---

## 🔐 Sistema de autenticación

- 🔑 Login seguro
- 👥 Roles de usuario
- 🛡️ Control de acceso
- 🔒 Protección de sesiones
- ⚡ Autenticación Django

---

## 🐳 Infraestructura moderna

- 🐳 Docker Compose
- ⚡ Entornos aislados
- 🔄 Desarrollo simplificado
- 🚀 Deploy escalable
- 📦 Contenedores optimizados

---

## 👨‍💻 Desarrollo colaborativo

- 🌿 Flujo Git profesional
- 🔀 Pull Requests
- 📋 Control de ramas
- 🧪 Entorno de pruebas
- ⚙️ Automatización de desarrollo

---

# 👨‍💻 Módulos del sistema

## 🔐 Authentication Module

Sistema de autenticación y permisos.

### Funcionalidades:

- Login seguro
- Roles de usuario
- Gestión de sesiones
- Protección de rutas
- Validación de acceso

---

## 👨‍🏫 Mentor Module

Gestión de mentores educativos.

### Funcionalidades:

- Administración de mentores
- Gestión de perfiles
- Control de acceso
- Seguimiento académico

---

## 👨‍👩‍👧 Guardian Module

Gestión de tutores y responsables.

### Funcionalidades:

- Registro de guardianes
- Asociación de estudiantes
- Administración de cuentas
- Gestión de accesos

---

## ⚙️ Admin Module

Panel administrativo principal.

### Funcionalidades:

- Gestión global
- Administración de usuarios
- Configuración del sistema
- Control organizacional

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,django" />
</p>

- Python 3
- Django
- Django ORM
- Django Authentication
- REST Architecture

---

## 🐳 DevOps & Infraestructura

<p>
  <img src="https://skillicons.dev/icons?i=docker" />
</p>

- Docker
- Docker Compose
- Containerized Development
- Environment Variables
- Virtualized Services

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=postgresql" />
</p>

- PostgreSQL
- Django ORM
- Relational Database
- Data Management

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,bash" />
</p>

- Git
- GitHub
- VS Code
- Bash
- Linux Environment

---

# 📂 Estructura del proyecto

```bash
we-all-code/
│
├── app/
│   ├── accounts/
│   ├── mentors/
│   ├── guardians/
│   ├── admin/
│   └── core/
│
├── docker/
│
├── static/
│
├── templates/
│
├── .env.sample
├── docker-compose.yml
├── manage.py
├── README.md
└── requirements.txt
```

---

# 🏗️ Arquitectura del sistema

## ⚡ Arquitectura general

```text
Usuario → Django Application → PostgreSQL Database
                     ↓
               Docker Containers
```

---

## 🔄 Flujo de autenticación

```text
Login → Validación Django → Sesión activa → Acceso autorizado
```

---

# 📊 Funcionalidades principales

## 👨‍🏫 Gestión educativa

- Administración de mentores
- Gestión de guardianes
- Control de usuarios
- Organización educativa

---

## 🔐 Seguridad

- Autenticación Django
- Protección de sesiones
- Roles y permisos
- Variables de entorno
- Secret Key segura

---

## 🐳 Docker Development

- Desarrollo en contenedores
- Configuración rápida
- Ambientes reproducibles
- Build automatizado

---

# 🔐 Seguridad del sistema

## 🛡️ Protección integrada

- 🔒 Django Authentication
- 🔑 SECRET_KEY protegida
- ⚡ Variables de entorno
- 🛡️ Docker isolation
- 🚫 Gestión de permisos
- 🔐 Protección backend

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3
- Docker
- Docker Compose
- Git
- VS Code

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/WeAllCode/website.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd website
```

---

## 3️⃣ Crear archivo .env

```bash
cp .env.sample .env
```

---

## 4️⃣ Generar SECRET_KEY

```bash
python -c "import secrets; print(secrets.token_urlsafe())"
```

Agregar la key al archivo `.env`

```env
SECRET_KEY="your-secret-key"
```

---

## 5️⃣ Ejecutar Docker

```bash
docker compose up --build
```

---

## 6️⃣ Abrir proyecto

```bash
http://127.0.0.1:8000
```

---

# 👤 Usuarios de prueba

## 🔑 Admin

```txt
username: admin@sink.sendgrid.net
password: admin
```

---

## 👨‍🏫 Mentor

```txt
username: mentor@sink.sendgrid.net
password: mentor
```

---

## 👨‍👩‍👧 Guardian

```txt
username: guardian@sink.sendgrid.net
password: guardian
```

---

# 💻 Comandos útiles

## 🐳 Ejecutar contenedor

```bash
docker compose run --rm app /bin/bash
```

---

## 📦 Migraciones

```bash
docker compose run --rm app python manage.py makemigrations
docker compose run --rm app python manage.py migrate
```

---

## 🧹 Limpiar contenedores

```bash
docker kill $(docker ps -q)
docker compose rm -f
```

---

## 🔄 Reconstruir proyecto

```bash
docker compose build
```

---

# 🌿 Flujo de desarrollo

## 🔀 Crear nueva rama

```bash
git fetch upstream --prune
git checkout -b feature/nueva-funcionalidad upstream/main
git push -u origin feature/nueva-funcionalidad
```

---

## 🔄 Actualizar desde upstream

```bash
git fetch upstream --prune
git checkout main
git merge upstream/main main
```

---

# 📸 Vista previa

## 🖥️ Plataforma educativa

<div align="center">

### 🎓 Dashboard administrativo
![Dashboard](https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=1200)

### 👨‍🏫 Gestión educativa
![Education](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200)

### 🐳 Infraestructura Docker
![Docker](https://images.unsplash.com/photo-1605745341112-85968b19335b?q=80&w=1200)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y desarrollo

- Arquitectura Django
- Docker Development
- Gestión educativa
- Backend escalable
- Sistemas multiusuario
- DevOps moderno
- Seguridad web

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- 🌐 API REST completa
- 📊 Analytics Dashboard
- ☁️ Cloud deployment
- 🔔 Sistema de notificaciones
- 🤖 Automatización educativa
- 📚 Gestión avanzada académica

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

# 👨‍💻 Desarrolladores

<div align="center">

## We All Code Community

Plataforma desarrollada por la comunidad We All Code para la gestión educativa y tecnológica 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source desarrollado para gestión educativa, aprendizaje colaborativo y administración organizacional con Django.

---

<div align="center">

### 🎓 We All Code Platform — educación y tecnología moderna 🚀

</div>
