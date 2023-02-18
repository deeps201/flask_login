# flask_login_authenctication

# Steps for Installation:
* Setup the virtual environment

      virtualenv -p python3 .venv

* Activate the virtual environment
    
      .venv/Scripts/activate

* Install Flask,Flask-Login,Flask-SQLAlchemy
    
      python -m pip install flask

      python -m pip install flask-login

      python -m pip install flask-sqlalchemy
      
* Setting Up the database
In the python shell

      from project import db, create_app, models
      db.create_all(app=create_app()) 

* Start the server

      flask --app project run

* To run the server====> http://127.0.0.1:5000



[CLICK HERE FOR DEMO VIDEO](https://drive.google.com/file/d/1XNG4zGU1ib3rpZOksb2iuyFqIv695q09/view?usp=sharing)
