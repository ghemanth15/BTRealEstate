# BTRealEstate
This is a simple real estate website that would have several realtors and each realtor is assigned a few listings. This project is developed using Django-(python based webframework) and i have used pgsql as the backend database querying language. Also, the project uses jinja template.

### For downloading django
```sh
pip install django
```
Creating virtual environment is not mandatory, but if you prefer a virtual environment , 
### Virtual Environment setup 
```sh
python -m venv venv
```
I've also downloaded pgAdmin v4 for viewing te database.
### The project can be run by using the following command 
```sh
python manage.py runserver
```
For any changes in static files ```sh python manage.py collectstatic ```
For changes in models.py ```sh python manage.py makemigrations ```
after performing makemigrations, do enter ```sh python manage.py migrate ``` to migrate all the changes to the database.
### For creating a superuser
```sh python manage.py createsuperuser ``` and then it asks for username,email,password and confirm password.
Incase of creating a django project in future ```sh django-admin startproject project_name ```
and creation of apps ```sh python manage.py app_name ```
Other operations and functionalities can be viewed by ```sh python manage.py help ```
The following are the links in the project domain:
> localhost:8000/admin --> To view the admin area
> localhost:8000/ --> To view the home page
> localhost:8000/about --> To view the about page
> localhost:8000/listings --> To view all the listings
> localhost:8000/listings/listing_id --> To view a specific lisiting
> localhost:8000/accounts/register --> To register
> localhost:8000/accounts/login --> To login
> localhost:8000/accounts/dashboard --> To view the dashboard of logged-in users
> localhost:8000/listings/search --> To search for listings of your choice
