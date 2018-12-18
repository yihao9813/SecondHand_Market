# SecondHand_Market
## A simple website that allow students trading of their unwanted items.


# Functions
* Registration & login
* Upload & remove products
* View & search the market
* Trading system
    * Sellers can view and manage their products via '交易管理'
    * Sellers have to confirm the trade after transactions have been done
    * View purchase & sales record

# Installing
### You are recommended develop under virtual environment
### At here, I have chosen virtualenv. For more info, please visit [here](https://packaging.python.org/guides/installing-using-pip-and-virtualenv/).

### Install packages needed via pip after activating virtualenv
```
pip install -r requirements.txt
```
### Create a database link edit config in dtiaozao/settings.py and run following command
```
python manage.py makemigrations
python manage.py migrate
```

### Run following command to run the project
```
python manage.py runserver
```
### Now you can view your development server at http://127.0.0.1:8000/ 

# Built with
* Python 3.6.6
* Django 1.8
* MySQL

## Visit [Django Documentation](https://docs.djangoproject.com/en/2.1/) for more info about deployment with django.

