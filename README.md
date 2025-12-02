<h1 align="center">Proyecto: Extracción y Análisis de Datos de Películas</h1>

<p align="center">
  Proyecto desarrollado dentro del bootcamp de <strong>Adalab</strong>, donde aprendemos extracción de datos, manejo de APIs, creación de bases de datos y consultas SQL.
</p>

---

## Descripción General

Este proyecto consiste en:

- Extraer 100 películas desde una API pública creada por Adalab.
- Procesar la información utilizando Python y almacenarla en un DataFrame.
- Crear una base de datos en MySQL (via Workbench o Python).
- Insertar los datos procesados en la base de datos.
- Analizar la información mediante consultas SQL.

---

## Herramientas Utilizadas

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="55" height="55"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VSCode" width="55" height="55"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="55" height="55"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="55" height="55"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="55" height="55"/>
</p>

---

## API

Endpoint de extracción: https://beta.adalab.es/resources/apis/pelis/pelis.json


Datos obtenidos:

- Título  
- Año de lanzamiento  
- Duración  
- Género  
- Contenido para adultos  

---

## Cómo Ejecutar el Proyecto

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/usuario/proyecto-peliculas.git
```
### 2️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```
### 3️⃣ Ejecutar la extracción de datos
```bash
python extract.py
```
### 4️⃣ Crear la base de datos
```bash
python create_db.py
```
### 5️⃣ Insertar los datos en MySQL
```bash
python insert_data.py
```
### 6️⃣ Ejecutar las consultas SQL en tu gestor MySQL
Incluyen:

- Películas >120 minutos
- Películas con subtítulos
- Películas con contenido adulto
- La película más antigua
- Promedio de duración por género
- Número de películas por año
- Año con más registros
- Conteo de películas por género
- Búsqueda por palabra clave (e.g. “Godfather”)


## Sobre Adalab

Adalab es una escuela que promueve la presencia de mujeres en el sector tecnológico mediante un modelo educativo práctico, colaborativo e inclusivo.

Este proyecto pertenece al módulo de Python + Bases de Datos.

## Autora

Proyecto desarrollado por: 
<p align="center">
  <a href="https://github.com/TamDb22">
    <img src="https://github.com/TamDb22.png" width="80" height="80" style="border-radius:50%;" alt="Tamara"/>
  </a>
</p>
<p align="center"><strong>✨ ¡Aprender es construir! ✨</strong></p> 
