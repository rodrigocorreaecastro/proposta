# proposta
https://www.youtube.com/watch?v=kLKl9IuLDV8&amp;list=WL&amp;index=31&amp;t=1373s

```
$ # Get the code
$ git clone https://github.com/wooddewweb/proposta.git
$ cd proposta
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install modules - MySQL Storage
$ pip3 install -r requirements.txt
$
$ # Create tables
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
$
$ # Start the app - custom port
$ # python manage.py runserver
$
$ # Access the web app in browser: http://127.0.0.1:8000/

```