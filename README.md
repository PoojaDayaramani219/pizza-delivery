# PIZZA DELIVERY API
This is a REST API for a Pizza delivery service built for fun and learning with FastAPI, SQLAlchemy and PostgreSQL.

# How to run the Project
- Install Postgreql
- Install Python
- Git clone the project with ``` git clone https://github.com/PoojaDayaramani219/pizza-delivery.git```
- Create your virtualenv `virtualenv` and activate it.
- Set Up your PostgreSQL database and set its URI in your ```database.py```
  
```
engine=create_engine('postgresql://postgres:<username>:<password>@localhost/<db_name>',
    echo=True
)
```

- Create your database by running ``` python init_db.py ```
- Finally run the API
``` uvicorn main:app ``
