# Advanced-Software-Engineering
Assignment 2

Click on this link to access my code https://nishchay1111.github.io/Advanced-Software-Engineering/


git clone https://github.com/Luko575/django-calculator-app.git
cd django-calculator-app

# -------------------------------------
# If you are on Windows
py -m venv env # or python -m venv env
.\env\Scripts\activate

# If you are on Linux or Mac
virtualenv env
source env/bin/activate
# -------------------------------------

pip install -r requirements.txt
py manage.py makemigrations # or python manage.py makemigrations
py manage.py migrate # or python manage.py migrate
py manage.py createsuperuser # or python manage.py createsuperuser
