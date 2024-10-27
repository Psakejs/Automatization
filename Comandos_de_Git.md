
# Comandos de Git
> **Nota:** La siguiente es una lista de comandos básicos y avanzados para trabajar con Git.

## Configuración Inicial

- `git --help`  
  Muestra la ayuda de Git.

- `git config --global init.defaultBranch main`  
  Establece "main" como la rama principal por defecto al inicializar un repositorio.

## Inicialización y Preparación de Archivos

- `git init`  
  Inicializa un repositorio en Git.

- `git add <archivo>`  
  Agrega un archivo al área de preparación (staging) para el próximo commit.

- `git add .`  
  Agrega todos los archivos al área de preparación.

## Realizar Commits

- `git commit -m "Mensaje"`  
  Crea un commit con un mensaje descriptivo.

- `git commit -am "Mensaje"`  
  Combina `git add .` y `git commit` en un solo comando (solo para archivos ya rastreados).

## Estado y Historial

- `git status`  
  Muestra el estado de los archivos en el área de preparación.

- `git show`  
  Muestra todos los cambios realizados.

- `git log`  
  Muestra el historial de commits.

- `git log --stat`  
  Muestra cambios específicos por archivo.

## Gestión de Ramas (Branches)

- `git branch <nombre>`  
  Crea una nueva rama.

- `git branch --list`  
  Lista todas las ramas.

- `git checkout <rama>`  
  Cambia a la rama especificada.

- `git merge <rama>`  
  Une la rama actual con otra rama.

## Repositorio Remoto

- `git clone <url>`  
  Clona un repositorio remoto.

- `git push origin <rama>`  
  Sube los cambios de una rama al repositorio remoto.

- `git pull origin <rama>`  
  Trae y combina los cambios de la rama remota.

## Resolución de Conflictos

> Durante un merge, elige las partes de código a conservar.

## Configuración de SSH

1. Genera una clave SSH con `ssh-keygen -t rsa -b 4096 -C "tuemail@example.com"`.
2. Agrega la clave con `ssh-add ~/.ssh/id_rsa`.
3. Conecta con GitHub usando `ssh -T git@github.com`.

## Tags

- `git tag <nombre>`  
  Crea un tag en la versión actual.

- `git push origin --tags`  
  Sube los tags al repositorio remoto.

## Ignorar Archivos con .gitignore

1. Crea un archivo `.gitignore` en el repositorio.
2. Agrega extensiones de archivos a ignorar, ej.: `*.jpg`, `*.png`.

## GitHub Pages

1. Crea un repositorio llamado `<usuario>.github.io`.
2. Sube un archivo `index.html`.
3. Configura GitHub Pages en las opciones del repositorio.

---

## Herramientas Avanzadas

- **Git Stash**: Guarda cambios temporales.
- **Git Reset**: Revierte el historial de commits.
- **Git Rebase**: Reorganiza commits (recomendado solo en repositorios locales).
- **GitHub Gist**: Comparte fragmentos de código.

---

Este archivo contiene una organización completa de los comandos Git esenciales y avanzados, así como configuraciones y prácticas recomendadas para el uso de Git y GitHub.
