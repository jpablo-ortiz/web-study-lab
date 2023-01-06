# Comandos de Git
## Inicialización de un repositorio
| Comando | Descripción |
| ------- | ----------- |
| `git init` | Inicializa un repositorio. |
| `git clone` | Clona un repositorio. |
## Flujo de archivos (cambios)
| Comando | Descripción |
| ------- | ----------- |
| `git add <archivo>` | Agrega un archivo al stage. |
| `git commit -m "Mensaje del commit"` | Crea un commit con un mensaje. |
| `git push <remoto> <rama>` | Sube los commits de una rama especifica al repositorio remoto. |
| `git pull <remoto> <rama>` | Trae los commits de una rama especifica del repositorio remoto. |
## Estado del repositorio
| Comando | Descripción |
| ------- | ----------- |
| `git status` | Muestra el estado del repositorio. |
| `git branch` | Muestra en una lista las ramas del repositorio. |
## Ramas
| Comando | Descripción |
| ------- | ----------- |
| `git checkout <rama>` | Se mueve a una rama. |
| `git checkout -b <rama>` | Crea una rama y se mueve a ella. |
| `git merge <rama>` | Une una rama a la rama actual. |
### Eliminar ramas
| Comando | Descripción |
| ------- | ----------- |
| `git branch -D <rama>` | Elimina una rama (forzosamente) del repositorio local. |
| `git push <remoto> --delete <rama>` | Eliminar la rama del repositorio remoto. |
## Otros
| Comando | Descripción |
| ------- | ----------- |
| `git log` | Muestra el historial de commits. |
| `git merge --abort` | Aborta un merge. |