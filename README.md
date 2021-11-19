# ⚗ Flask Web Development: Mis prácticas

Resultados de mis prácticas con el libro de Miguel Grinberg.

## 📕 Capítulos vistos en la parte 1

1. Installation
2. Basic Application Structure
3. Tempaltes
4. Web Forms
5. Databases
6. Email

Los capítulos del 1 al 6 están en la rama principal (`part1/caps1-6`), pero el capítulo 7 lo hago en una rama distinta (`part1/cap7`) debido a que cambia bastante su estructura!


## 🏃‍♂️ Instalar y correr Flask App

- Primero clonamos el repositorio

```
git clone https://github.com/JaviCeRodriguez/flask_practice.git
cd ./flask_practice
```

- Seteamos las variables de entorno (con PowerShell, trabajo con Windows 😅)

```
$env:FLASK_APP = "hello.py"
$env:FLASK_DEBUG = "1"
$env:MAIL_USERNAME="gmail_username"
$env:MAIL_PASSWORD="gmail_password_application"
$env:JAVO_ADMIN="mi_usuario@gmail.com"
```

- Creamos entorno virtual e instalamos las librerías adentro
```
python -m venv venv
venv/Scripts/activate
(venv) pip install -r requirements.txt
```

- Por último, corremos la aplicación

```
(venv) flask run
```

Abrimos el browser de preferencia y entramos a [http://127.0.0.1:5000/](http://127.0.0.1:5000/)