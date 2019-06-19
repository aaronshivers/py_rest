# py_rest
A RESTful API with Flask, SQL Alchemy, and Marshmallow

## Setup

### Start Virtual Environment
```
pipenv shell
```

### Install Dependencies
```
pipenv install
```

### Create Database
```
python
from app import db
db.create_all()
exit()
```

### Run Server
http://localhost:5000
```
python app.py
```

## Routes
+ POST /products
+ GET /products
+ GET /products/:id
+ PUT /products/:id
+ DELETE /products/:id
