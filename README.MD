# Game Project

Para correr el juego, debes seguir las siguientes instrucciones en la terminal:

```sh
cd game
python3 main.py
```

# Charts Project

Para correr la gráfica, debes seguir las siguientes instrucciones en la terminal:

```sh
cd charts
python3 main.py
```

Y la gráfica generada estará en `pie.png`

# App Project

Para correr la app, debes seguir las siguientes instrucciones en la terminal:

```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```

# Contenedores con Docker

Para usar este proyecto en su contenedor Docker, hay que usar:

```sh
❯ docker-compose build
❯ docker-compose exec app-csv bash
❯ docker-compose ps
```

En donde `app-csv` es el nombre del chart project
