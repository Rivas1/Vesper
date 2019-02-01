# Vesper
Version 1.0

Built with:
-Python 3.6.3

**Pip list:**
 
------------ -------
- Django       2.1.5
- django-jinja 2.4.1
- Jinja2       2.10
- MarkupSafe   1.1.0
- mysqlclient  1.4.1
- pip          19.0.1
- pytz         2018.9
- setuptools   40.7.2
- wheel        0.32.3


Folder structure
1. Vesper
   - Vesper (this repository)
   - Vehicles (download matching version 1.0)

Then wrap inside Vesper parent folder

Github backed up second Vesper so you must download Vehicles repository as well.

Vehicles may be added through backend.
localhost/vehicles --> displays current list
localhost/vehicles/details --> display info on vehicle


Once downloaded, open command line:
- cd Vesper
- workon py2 ( remember to set up and create a virtual env )
- python manage.py runserver
