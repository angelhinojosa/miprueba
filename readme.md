# Entrega Git

## 1. Crear un repositorio en local
### ruta -> /Users/ahh/Desktop/Cursos/LemonCode/
### mkdir miprueba
### ruta -> /Users/ahh/Desktop/Cursos/LemonCode/miprueba
### git init
### git add .
### git commit -m "hola git"

## 2. Subir el repositorio a GitHub

<img src="./images/captura_repo.png" alt="Imagen Repositorio" title="Imagen Repositorio" />

###  git@github.com:angelhinojosa/miprueba.git
<p>He configurado la conexión ssh</p>

### git clone git@github.com:angelhinojosa/miprueba.git

<img src="./images/verificar_conexion.png" alt="Imagen Conexion" title="Imagen Conexión">

## 3. Hacer un commit y un push

<p>Creo la carpeta images para guardar las capturas.</p>

### git init
### git add .
### git commit -m "Añado carpeta images"
### git push

<img src="./images/hacer commit y push.png" alt="Captura Commit Push" title="Captura Commit Push">

<br>

<img src="./images/captura commit.png" alt="Caputa Commit en remote" title="Captura Commit en remote">

## 4. Crear una rama

### git brach development

### git checkout development

<img src="./images/Captura rama development.png" alt="Captura rama Development" tiitle="Captura rama Development">

### git add .

### git commit -a -m "Añado captura rama Development"

### git push

<img src="./images/Captura push development.png" alt="Captura push Development"
title="Captura push Development">

## 5. Hacer un merge

### git checkout main

### git merge development -m "mezclado development businees.js"

### git push

<p> Vuelvo a repetir creando una nueva rama para ver si consigo ver porque
no me muestra el dibujo de las ramas con el git log..... Rama Prueba 1</p>















