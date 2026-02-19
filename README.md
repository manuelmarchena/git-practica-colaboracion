# Proyecto final Git y Github - Talento Tech 
# Crear un repositorio y añadir cambios a través de Git y Github
Autor: Manuel Marchena

# Pasos seguidos
1. Inicialización del repositorio local
git init
git add .
git commit -m "Initial commit"
git branch -M main

2. Creación del repositorio remoto desde Github 

3. Verificación del estado del repositorio
git status

4. Creación de una rama de desarrollo
git checkout -b feature/readme-mejora

5. Modificación del proyecto y commit de cambios
git add .
git commit -m "feat: mejora README con descripcion del flujo"

6. Publicación de la rama de feature
git push -u origin feature/readme-mejora


La rama quedó disponible en GitHub para revisión mediante Pull Request.

7. Creación y fusión del Pull Request en GitHub

Desde la interfaz web de GitHub:
Se creó un Pull Request hacia main
Se revisaron los cambios
Se realizó el merge de la feature