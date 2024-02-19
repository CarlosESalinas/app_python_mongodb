# UFO Tracking App

Este proyecto es una aplicación web desarrollada con Python, Flask y MongoDB para el seguimiento de avistamientos de objetos voladores no identificados (OVNIs). 
La aplicación permite a los usuarios consultar y cargar nuevos datos sobre avistamientos de OVNIs mediante un formulario de consulta y otro de registro, respectivamente. 
Los datos registrados son almacenado y organizados en una base de datos MongoDB.

## Requisitos previos

- Python instalado en tu sistema. Puedes descargarlo desde [aquí](https://www.python.org/downloads/).
- MongoDB instalado en tu sistema. Puedes encontrar instrucciones de instalación en [este enlace](https://docs.mongodb.com/manual/installation/).
- MongoDB Compass.
- MongoDB Atlas, libre o por pago. 
- Flask y otras dependencias de Python instaladas. Puedes instalarlas ejecutando el siguiente comando en tu terminal:


```bash
pip install -r requirements.txt
```

## Configuración

1. Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/CarlosESalinas/app_python_mongodb
```

2. Abre el proyecto en tu editor de código favorito.

3. Crea un archivo `.env` en la raíz del proyecto y agrega la siguiente configuración:

```plaintext
MONGO_URI=<Tu URI de conexión a MongoDB>
```

4. Asegúrate de tener una base de datos MongoDB creada para la aplicación.

## Ejecución

1. Desde la terminal, navega hasta el directorio raíz del proyecto.

2. Ejecuta la aplicación con el siguiente comando:

```bash
set FLASK=app.py
run flask
```

3. Abre un navegador web y ve a `http://localhost:5000` para acceder a la aplicación.

## Uso

- La aplicación permite a los usuarios consultat y cargar datos sobre avistamientos de OVNIs utilizando el formulario de consulta y otro de registro.
- Los datos cargados se organizan y almacenan en la base de datos MongoDB especificada.
- Los usuarios pueden ver la lista de avistamientos de OVNIs en la página principal y realizar búsquedas por diferentes criterios.

## Muestra de la aplicación 


[![Alt text](https://img.youtube.com/vi/VvGRgHIcRfU/0.jpg)](https://www.youtube.com/watch?v=VvGRgHIcRfU)




## Fuentes
Pra más información sonbre la app, puedes consultar [aquí](https://www.mongodb.com/developer/languages/python/flask-app-ufo-tracking/#submit-new-ufo-sighting-and-write-to-database).<br>
Para más información sobre la base de datos, puedes consulta [aquí](https://www.kaggle.com/datasets/NUFORC/ufo-sightings?select=scrubbed.csv).
