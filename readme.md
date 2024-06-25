# Entrega Git

## 1. Crear un repositorio en local

```bash
# ruta -> /Users/ahh/Desktop/Cursos/LemonCode/
mkdir miprueba
# ruta -> /Users/ahh/Desktop/Cursos/LemonCode/miprueba
git init
git add .
git commit -m "hola git"
```


## 2. Subir el repositorio a GitHub

<img src="./images/captura_repo.png" alt="Imagen Repositorio" title="Imagen Repositorio" />

<br>

<p>Configurado la conexión ssh: git@github.com:angelhinojosa/miprueba.git y hago la conexión:</p>

```bash
git remote add origin git@github.com:angelhinojosa/miprueba.git
git push -u origin main
```

<br>

<img src="./images/verificar_conexion.png" alt="Imagen Conexion" title="Imagen Conexión">

## 3. Hacer un commit y un push

<p>Creo la carpeta images para guardar las capturas.</p>

```bash
git init
git add .
git commit -m "Añado carpeta images"
git push
```

<br>

<img src="./images/hacer commit y push.png" alt="Captura Commit Push" title="Captura Commit Push">

<br>

<img src="./images/captura commit.png" alt="Caputa Commit en remote" title="Captura Commit en remote">

## 4. Crear una rama

```bash
git branch development
git checkout development
# git checkout -b development
```
<br>

<img src="./images/Captura rama development.png" alt="Captura rama Development" tiitle="Captura rama Development">
<br>

```bash
git add .
git commit -a -m "Añado captura rama Development"
git push
```
<br>

<img src="./images/Captura push development.png" alt="Captura push Development"
title="Captura push Development">
<br>

## 5. Hacer un merge
```bash
git checkout main
git merge development -m "mezclado development businees.js"
git push
```
<br>
<p> Vuelvo a repetir creando una nueva rama para ver si consigo ver porque
no me muestra el dibujo de las ramas con el git log..... Rama Prueba 1</p>

<p> Nada no lo consigo, adjunto captura.</p>

<img src="./images/Captura merge_git log.png" alt="Captura merge prueba1"
title="Captura merge prueba1">













