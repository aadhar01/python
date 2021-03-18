# python #django
just some basics

in powershell
check python version with
> python -v
> python -m pip install --upgrade pip
> cd dev\trydjango
directory changed

create virtual environment
> python -m venv venv
> venv\scripts\activate  /*start venv*/

install django
> python -m install django==2.0.7
to check install use 
> pip freeze
change src
> mkdir src
> cd src
> django-admin startproject trydjango .
> python manage.py runserver
> 

apps are components of the project
models.py : model is a single definitive source of information about your data, it contains the essential fileds and behaviours of data you are storing

generally each model maps to single database table.
