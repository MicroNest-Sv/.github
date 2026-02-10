<p align="center">
  <img src="../resources/catppuccin--nest.svg" width="200" alt="NestJS Logo" align="middle" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="../resources/icon-park--plus.svg" width="80" alt="Plus" align="middle" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="../resources/carbon--microservices-1.svg" width="200" alt="Microservices Logo" align="middle" />
</p>

<h1 align="center">NestJS + Microservicios</h1>

<p align="center">Guía completa de instalaciones y configuración para desarrollo de Microservicios con NestJS</p>

---

## 📋 Requisitos Previos

### Herramientas Esenciales

> [!IMPORTANT]
> Asegúrate de tener instaladas las siguientes herramientas antes de comenzar:

| Herramienta            | Descripción                  | Link de Descarga                                |
| ---------------------- | ---------------------------- | ----------------------------------------------- |
| **Visual Studio Code** | Editor de código recomendado | [Descargar](https://code.visualstudio.com/)     |
| **Node.js**            | Runtime de JavaScript        | [Descargar](https://nodejs.org/en)              |
| **Docker Desktop**     | Plataforma de contenedores   | [Descargar](https://www.docker.com/get-started) |
| **Git**                | Control de versiones         | [Descargar](https://git-scm.com/)               |

### Configuración Inicial de Git

> [!NOTE]
> Configura Git con tu información personal antes de comenzar:

```bash
git config --global user.name "Tu nombre"
git config --global user.email "Tu correo"
```

---

## 🚀 Instalación de NestJS CLI

Para instalar NestJS CLI globalmente en tu sistema:

```bash
npm i -g @nestjs/cli
```

Verifica la instalación:

```bash
nest --version
```

---

## 🐳 Imágenes Docker Requeridas

> [!IMPORTANT]
> Descarga las imágenes Docker necesarias para trabajar con microservicios:

```bash
# MongoDB v7.0
docker pull mongo:7.0

# PostgreSQL v16.2
docker pull postgres:16.2

# NATS (Sistema de mensajería)
docker pull nats:latest
```

> [!TIP]
> Estas imágenes son fundamentales para la comunicación entre microservicios y la gestión de bases de datos

---

## 🛠️ Herramientas Opcionales (Recomendadas)

### Clientes de Base de Datos

| Herramienta       | Descripción              | Link                                                    |
| ----------------- | ------------------------ | ------------------------------------------------------- |
| **DataGrip**      | Cliente universal de BD  | [Descargar](https://www.jetbrains.com/datagrip/)        |
| **Mongo Compass** | Cliente GUI para MongoDB | [Descargar](https://www.mongodb.com/try/download/shell) |

### Clientes API

| Herramienta  | Descripción              | Link                                            |
| ------------ | ------------------------ | ----------------------------------------------- |
| **Postman**  | Cliente HTTP completo    | [Descargar](https://www.postman.com/downloads/) |
| **Insomnia** | Cliente HTTP minimalista | [Descargar](https://insomnia.rest/)             |

---

## 📚 Recursos de Aprendizaje

### Hoja de Atajos

> [!TIP]
> Descarga la hoja de atajos oficial de NestJS para tener a mano los comandos más importantes:
>
> **[📄 NestJS Cheat Sheet](https://github.com/Klerith/mas-talento/blob/main/nest/nest-cheatsheet.pdf)**

---

## 🎨 Configuración del Editor

### Tema Visual Studio Code

Para una mejor experiencia visual, se recomienda:

| Componente | Nombre                                                                                               |
| ---------- | ---------------------------------------------------------------------------------------------------- |
| **Tema**   | [Aura Theme](https://marketplace.visualstudio.com/items?itemName=DaltonMenezes.aura-theme)           |
| **Iconos** | [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) |

### Configuración de Iconos para NestJS

> [!IMPORTANT]
> Para mostrar iconos de Nest en lugar de Angular, agrega esto en tu `settings.json`:

**Para VSCode**, presiona `Ctrl + Shift + P` → `Preferences: Open Settings (JSON)` y agrega:

```json
{
  "material-icon-theme.activeIconPack": "nest"
}
```

## 🎯 Configuración de Iconos Catppuccin

### Asociaciones de Archivos NestJS

> [!IMPORTANT]
> Para tener los iconos correctos asociados a los archivos de NestJS, agrega esta configuración a tu editor:

**Para VSCode**, agrega esto en tu `settings.json`:

```json
{
  "catppuccin-icons.associations.extensions": {
    "module.ts": "nest",
    "controller.ts": "nest-controller",
    "service.ts": "nest-service",
    "decorator.ts": "nest-decorator",
    "filter.ts": "nest-filter",
    "gateway.ts": "nest-gateway",
    "guard.ts": "nest-guard",
    "middleware.ts": "nest-middleware",
    "pipe.ts": "nest-pipe",
    "interceptor.ts": "nest-decorator",
    "adapter.ts": "nest",
    "spec.ts": "typescript-test",
    "e2e-spec.ts": "typescript-test"
  }
}
```

> [!NOTE]
> Esta configuración requiere tener instalada la extensión [Catppuccin Icons](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons)

---

## 🔌 Extensiones Recomendadas

### Extensiones Esenciales

> [!NOTE]
> Instala estas extensiones para mejorar tu productividad:

| Extensión              | Descripción                                            | Link                                                                                                |
| ---------------------- | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| **Paste JSON as Code** | Convierte JSON a interfaces TypeScript automáticamente | [Instalar](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)                 |
| **DotENV**             | Resaltado de sintaxis para archivos .env               | [Instalar](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)                    |
| **Better Dockerfile**  | Mejor sintaxis para Dockerfiles                        | [Instalar](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-dockerfile-syntax) |

---

## 📖 Sobre este Repositorio

Este repositorio contiene notas y prácticas sobre:

- ✅ Arquitectura de Microservicios con NestJS
- ✅ Comunicación entre servicios (NATS, RabbitMQ, Kafka)
- ✅ Patrones de diseño en sistemas distribuidos
- ✅ Docker y contenedorización
- ✅ API Gateways y BFF (Backend for Frontend)
- ✅ Manejo de bases de datos distribuidas

> [!NOTE]
> Repositorio personal de aprendizaje y referencia

---

<p align="center"><i>"La simplicidad es la sofisticación máxima"</i> — Leonardo da Vinci</p>
