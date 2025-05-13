# 📝 Introducción

Para esta semana la tarea consiste en desarrollar código para una aplicación muy simple. Una aplicación de **TODOLIST** con un **CRUD básico** en el que trabajaremos con las operaciones: **CREATE**, **READ**, **UPDATE** y **DELETE**. Una única página y sin login, pero si se necesita base de datos con una colección "Todos". Es muy **IMPORTANTE** y **NECESARIO** ver los tutoriales para saber cómo cumplir los requerimientos de la aplicación. 

> **Nota**: Para el desarrollo de la aplicación deben de elegir entre **Cursor** o **Windsurf**, el editor que ustedes quieran.

## 🖥️ Explicación de Cursor

[Cursor](https://www.cursor.com/) consiste en un IDE para trabajar con código basado en Visual Studio Code. La comunidad de desarrolladores está migrando poco a poco a este nuevo editor y está despertando mucho interés recientemente. Cuenta con varias funcionalidades pero la más importante es la **integración de un agente de IA** a través de una interfaz tipo chat que ustedes ya conocen bastante bien. 

## 🌊 Explicación de Windsurf

[Windsurf](https://windsurf.com/editor) se basa en las mismas ideas que el editor anterior. Ha tenido muchos cambios recientemente y está evolucionando muy rápido, tanto que OpenAI quiere comprar el editor. También cuenta con un **agente de IA** dentro del editor.

## ✅ Requerimientos

- Empleo del **Stack MERN**: 
  - **M**ongo 
  - **E**xpress 
  - **R**eact 
  - **N**ode
- Uso de **Docker** y **Docker compose** (muy aconsejable configurarlo con WSL)
- Uso de **Cursor** o **Windsurf** como editores de código
- Empleo de **Gitsubmodules** para separar frontend y backend en dos repositorios diferentes en total harían falta 3 repositorios:
  - Frontend
  - Backend 
  - Repositorio padre que se encargará de llamar a los dos repositorios anteriores, este repositorio tras el **FORK** será el repositorio padre.
- Emplear **agente por chat** del editor con el que estén trabajando para trabajar con el código que desarrollen y probar la potencia de la herramienta

## 📚 Tutoriales

### 🖥️ Cursor
[![Cursor Tutorial](https://img.youtube.com/vi/SM8040cwBdw/0.jpg)](https://www.youtube.com/watch?v=SM8040cwBdw)

### 🌊 Windsurf
[![Windsurf Tutorial](https://img.youtube.com/vi/3qi94lCdYI0/0.jpg)](https://www.youtube.com/watch?v=3qi94lCdYI0)

### 🐳 Docker y Docker Compose
[![Docker y Docker Compose Tutorial](https://img.youtube.com/vi/4Dko5W96WHg/0.jpg)](https://www.youtube.com/watch?v=4Dko5W96WHg)

### 🐧 Configurar Docker con WSL
[![Configurar Docker con WSL Tutorial](https://img.youtube.com/vi/urP3766-qQY/0.jpg)](https://www.youtube.com/watch?v=urP3766-qQY)

### 🔄 Configurar gitsubmodules
[![Configurar gitsubmodules Tutorial](https://img.youtube.com/vi/gSlXo2iLBro/0.jpg)](https://www.youtube.com/watch?v=gSlXo2iLBro)

## 💡 Consejo de Docker

> **Importante**: Recomiendo utilizar archivos **Dockerfile** (`.dockerfile`) y **Docker compose** (`.yaml`)

Aconsejo entender la arquitectura de la aplicación para desarrollar los servicios en el archivo docker compose y la configuración específica de cada uno en los archivos dockerfile.

> **Pista: Hay que hacer 3 servicios!!**