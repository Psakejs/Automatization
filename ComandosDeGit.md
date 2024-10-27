
# Comandos de Git

> **Nota:** Este archivo contiene una lista detallada de comandos de Git y su funcionalidad, junto con configuraciones avanzadas.

## Configuración Básica

- `$ git --help`  
  Muestra una lista de ayuda con todos los comandos de Git.

- `$ git config --global init.defaultBranch main`  
  Define `main` como la rama principal por defecto al inicializar repositorios.

## Inicialización y Preparación de Archivos

- `$ git init`  
  Inicializa un nuevo repositorio en el directorio actual.

- `$ git add <archivo>`  
  Agrega un archivo al área de staging para ser incluido en el próximo commit.

- `$ git add .`  
  Agrega todos los archivos del directorio actual al área de staging.

## Commits

- `$ git commit -m "Mensaje"`  
  Realiza un commit con un mensaje descriptivo.

- `$ git commit -am`  
  Añade y hace commit en un solo paso (solo funciona si el archivo ya ha sido rastreado).

## Estado y Cambios

- `$ git status`  
  Muestra el estado del área de staging y los cambios en los archivos.

- `$ git show`  
  Muestra todos los cambios realizados hasta el momento.

- `$ git log`  
  Muestra el historial de commits.

## Ramas (Branches)

- `$ git branch <nombre>`  
  Crea una nueva rama.

- `$ git checkout <rama>`  
  Cambia a otra rama.

- `$ git merge <rama>`  
  Fusiona una rama con la actual.

- `$ git branch -d <rama>`  
  Elimina una rama.

## Repositorio Remoto

- `$ git clone <url>`  
  Clona un repositorio remoto.

- `$ git push origin <rama>`  
  Sube los cambios de la rama al repositorio remoto.

- `$ git pull origin <rama>`  
  Trae los cambios de la rama remota y los fusiona.

## Rebase

- `$ git rebase <rama>`  
  Reorganiza los commits de la rama base en la actual.

## Stash

- `$ git stash`  
  Guarda temporalmente los cambios sin hacer commit.

- `$ git stash pop`  
  Restaura los cambios guardados en stash.

## Configuración de SSH y Llaves

- `ssh-keygen -t rsa -b 4096 -C "tuemail@ejemplo.com"`  
  Genera una nueva llave SSH para autenticar en GitHub.

- `$ ssh-add ~/.ssh/id_rsa`  
  Agrega la llave privada al entorno local.

## Otros Comandos Útiles

- `$ git tag <nombre>`  
  Crea un tag para marcar una versión específica en el historial de commits.

- `$ git reset`  
  Restaura el repositorio a un estado anterior.

- `$ git clean -f`  
  Elimina archivos no rastreados en el repositorio.

---

## Recursos Adicionales

- **GitHub Pages:**  
  Publica un sitio web estático directamente desde un repositorio de GitHub.

- **GitHub Projects:**  
  Herramienta de gestión de proyectos integrada en GitHub.

- **GitHub Gist:**  
  Comparte fragmentos de código o notas rápidas con otros.

---

_Este documento fue generado para organizar y facilitar el aprendizaje de comandos de Git._
