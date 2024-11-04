Soy Matheus 😊.
# Guía Básica de Comandos Git 📘

![Logo de Git](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

¡Hola! Soy Matheus 😊. Aquí tienes una guía rápida y visual sobre los comandos esenciales de Git. 

---

## 📌 Comenzando con Git

### 1. Configuración Inicial 🛠️
\```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@dominio.com"
\```
> Configura tu nombre y correo para los commits.


### 2. Crear un Repositorio Nuevo 🆕
\```bash
git init
\```
> Inicia un nuevo repositorio en el directorio actual.

---

## 🌱 Flujo de Trabajo Básico

### 3. Clonar un Repositorio 🌀
\```bash
git clone <url_del_repositorio>
\```
> Crea una copia local de un repositorio remoto.


### 4. Ver el Estado del Repositorio 📋
\```bash
git status
\```
> Muestra el estado actual del repositorio, incluyendo archivos modificados y no rastreados.


### 5. Añadir Archivos al Área de Staging ➕
\```bash
git add <nombre_del_archivo>
# O para añadir todos los cambios:
git add .
\```
> Mueve los cambios al área de staging, preparándolos para el commit.


### 6. Confirmar Cambios con un Commit 📦
\```bash
git commit -m "Mensaje descriptivo del cambio"
\```
> Guarda los cambios en el historial del repositorio.


---

## 🔄 Trabajando con Ramas

### 7. Crear una Nueva Rama 🌿
\```bash
git branch <nombre_de_la_rama>
\```
> Crea una nueva rama para trabajar en paralelo sin afectar la rama principal.


### 8. Cambiar de Rama 🔀
\```bash
git checkout <nombre_de_la_rama>
\```
> Mueve el trabajo a otra rama.


### 9. Fusionar Ramas 🧩
\```bash
git merge <nombre_de_la_rama>
\```
> Fusiona los cambios de una rama en la rama actual.


---

## 🌍 Trabajando con Repositorios Remotos

### 10. Subir Cambios al Remoto 📤
\```bash
git push origin <nombre_de_la_rama>
\```
> Sube tus commits a la rama especificada del repositorio remoto.


### 11. Actualizar Repositorio Local con Cambios Remotos 📥
\```bash
git pull origin <nombre_de_la_rama>
\```
> Trae y aplica los cambios de una rama remota a la rama local actual.


---

## 📊 Comandos Adicionales

### 12. Ver el Historial de Commits 📜
\```bash
git log
\```
> Muestra una lista de commits realizados en el proyecto.


### 13. Ver Diferencias entre Cambios 🧐
\```bash
git diff
\```
> Muestra las diferencias entre los cambios realizados.


### 14. Deshacer Cambios en el Área de Staging 🚫
\```bash
git reset <nombre_del_archivo>
\```
> Quita el archivo del área de staging, manteniendo los cambios en el directorio de trabajo.


---

## 🎉 ¡Felicidades! Ya tienes una base sólida para usar Git. 🎉

![GIF Divertido](https://media.giphy.com/media/26ufdipQqU2lhNA4g/giphy.gif)

¡Espero que esta guía te sea útil para manejar tus proyectos de Git con éxito!
