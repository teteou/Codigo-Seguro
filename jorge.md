https://github.com/jorgerubin
Autor: Jorge Rubin Roger

# Inicializar un repositorio
git init

# Clonar un repositorio
git clone <url>

# Ver estado de archivos
git status

# Añadir archivo al staging
git add <archivo>

# Añadir todos los archivos al staging
git add .

# Realizar un commit
git commit -m "Mensaje del commit"

# Ver historial de commits
git log

# Ver historial en una línea
git log --oneline

# Añadir y realizar commit en un solo paso
git commit -am "Mensaje del commit"

# Revertir cambios en archivo sin agregar al staging
git checkout -- <archivo>

# Crear una nueva rama
git branch <nombre-rama>

# Cambiar a una rama
git checkout <nombre-rama>

# Crear y cambiar a una nueva rama
git checkout -b <nombre-rama>

# Fusionar una rama con la actual
git merge <nombre-rama>

# Eliminar una rama
git branch -d <nombre-rama>

# Añadir remoto
git remote add origin <url>

# Enviar cambios al remoto
git push origin <nombre-rama>

# Descargar cambios desde el remoto
git pull origin <nombre-rama>