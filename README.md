# ejercicios-python
Este es un proyecto donde trae algunos ejercicios básicos de python del [curso de python de platzi](https://platzi.com/cursos/python-pip/)

## Inicio
Para iniciar con el proyecto

```sh
git clone
```

## Proyectos

### Game
Para iniciar el juego de piedra, papel y tijeras

```sh
cd game
python3 main.py
```

### charts
Crear un grafico simple de pie, para inicar:

```sh
cd charts
python3 main.py
```

### app
Obtener un grafico historico de la población de un pais, para iniciar:

```sh
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```

### web-server
Ejemplo para traer datos de una API de platzi y creando una propia con FastAPI, para iniciar

```sh
cd web-server
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```

En el link `http://127.0.0.1:8000/` se puede consultar nuestra API, que regresar algunas lista y en `http://127.0.0.1:8000/pagina` retorna un HTML sencillo.


