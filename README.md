# djangosqldb
note:- feel free to add your design in it by clonning it.


**Django SQL Database with Login, Logout, Account Creation, Photo Uploading, and Photo Fetching**

**Overview**

This is a simple Django project that demonstrates how to use a SQL database to implement login, logout, account creation, photo uploading, and photo fetching. The project uses the following technologies:

* Django
* MySQL
  

**Installation**

Additional installation required for this project:

```
pip install mysql (maybe it get updated so please visit offcial site of python mysql installation)
python manage.py migrate
python manage.py createsuperuser
```

Once the project is installed, you can start the development server by running the following command:

```
python manage.py runserver
```

The project will be running on http://localhost:8000/ by default.


**Notes**

* This project is just a starting point. You will need to customize it to meet your specific needs.
* The project is currently using MySQL as the database. You can change the database to something else by editing the `DATABASES` setting in the `settings.py` file.
* You can change the image processing library to something else by editing the `INSTALLED_APPS` setting in the `settings.py` file.

