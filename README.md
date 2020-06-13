# Monk Store :credit_card:
A fully functional eCommerece website with user and guest checkout capabilities.

![alt text](https://raw.githubusercontent.com/anilkaundal/monk-store/master/demo.gif)

#### Steps to running the project: 
- Clone the project.

  ```git clone https://github.com/anilkaundal/monk-store.git```
- Create and start a a virtual environment.
  ```
  virtualenv env --no-site-packages
  source env/bin/activate 
  ```
- Install the project dependencies.

  ```pip install -r requirements.txt```

- Then run.

  ```python manage.py migrate```
- Create admin account.

  ```python manage.py createsuperuser```
- Make migrations for the app.

  ```python manage.py makemigrations store```
- Then again run.

  ```python manage.py migrate ``` 
- To start the development server.
  ```python manage.py runserver```
#### Open ```localhost:8000``` on your browser to view the app.

  

