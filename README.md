## Usage

```git clone https://github.com/strongSoda/DjangoJwtAuthReact.git```

## Setting Up Backend

```cd pyReactJwtAuth```

Install pipenv 

```bash
sudo apt install pipenv
```

Create a python env with ```pipenv install``` in the project root

start the shell ```pipenv shell```

install the dependencies

```python
pipenv install django
pipenv install djangorestframework
pipenv install djangorestframework-jwt
pipenv install django-cors-headers
```

Make mugration ```python manage.py migrate```

Start the server 

```python manage.py runserver```

## Setting up Frontend

`cd reactClient`

```npm i ```

```npm start```

go to localhost 3000 in browser.

