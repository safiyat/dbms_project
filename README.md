dbms_project
============

This is a Django based Stock Market trading portal, designed in completion of DBMS project.




Setting up the Environment
==========================

The development is being done using

    Python 2.7.5 (http://www.python.org/download/releases/2.7.5/)
    Django 1.5.1 (https://pypi.python.org/pypi/Django/1.5.1)
    MySQL 5.5.32 (http://dev.mysql.com/downloads/mysql/5.5.html)
    MySQL-python 1.2.4 (https://pypi.python.org/pypi/MySQL-python)
    Django Registration 1.0 (https://pypi.python.org/pypi/django-registration)

    
Satisfy all the above pre-requisites, then

    Setup the database:
        Create a database in your MySQL DBMS by the name dbms_project (or any other name, as specified in settings.py, line 15).
        Provide the user and password to the database in the same file, (line no. 17, 18).

    Sync your django project with the database as:
        $ python manage.py syncdb
        
    Run the project as:
        $ python manage.py runserver
