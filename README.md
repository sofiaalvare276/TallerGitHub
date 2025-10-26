# TallerGitHub
sofia 
Este es un proyecto para aprender a usar GitHub, creando un repositorio, ramas para expadir conocimientos.

## Reto Final: Subir proyecto AquaElite y trabajar con ramas

Este reto consistió en subir un proyecto personal (`index.html` y carpeta `img`) a GitHub, crear dos ramas con mejoras, fusionarlas y documentar el proceso. A continuación, te detallo los pasos realizados:

1. **Preparar el repositorio local**:
   - Verifiqué que el repositorio en `TallerGitHub` estuviera inicializado con `git status`.
   - Agregué `index.html` y la carpeta `img` con las imágenes usando `git add .`.
   - Hice un commit inicial: `git commit -m "Añadir index.html y carpeta img con imágenes para AquaElite"`.

2. **Subir el proyecto a GitHub**:
   - Subí la rama `main` al repositorio remoto con `git push origin master`.
   - Verifiqué en GitHub que los archivos estaban en el repositorio.

3. **Crear primera rama (`feature-footer`)**:
   - Creé la rama `feature-footer` con `git checkout -b feature-footer`.
   - Modifiqué `index.html` para añadir un footer con información de contacto y derechos de autor.
   - Hice commit: `git commit -m "Añadir footer con información de contacto y derechos de autor"`.
   - Subí la rama: `git push origin feature-footer`.

4. **Crear segunda rama (`feature-button`)**:
   - Volví a `master` con `git checkout master`.
   - Creé la rama `feature-button` con `git checkout -b feature-button`.
   - Modifiqué `index.html` para añadir un botón de inscripción en la sección hero.
   - Hice commit: `git commit -m "Añadir botón de inscripción en la sección hero"`.
   - Subí la rama: `git push origin feature-button`.

5. **Fusionar las ramas**:
   - En GitHub, creé un Pull Request para `feature-footer` con título “Añadir footer a index.html” y lo fusioné en `master`.
   - Actualicé el repositorio local con `git pull origin master`.
   - Creé un Pull Request para `feature-button` con título “Añadir botón en sección hero” y lo fusioné en `master`.
   - Actualicé nuevamente el repositorio local con `git pull origin master`.

6. **Documentar el proceso**:
   - Actualicé este `README.md` para incluir los pasos del reto final.
   - Agregué los cambios con `git add README.md` y commit: `git commit -m "Documentar el proceso del reto final en README.md"`.
   - Subí los cambios a GitHub con `git push origin master`.