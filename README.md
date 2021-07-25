# Freelancer django
A website where people can get and provide freelance services.

## How to set up the project?
```
git clone git@github.com:ali-sajjad-rizavi/freelancer_django.git
cd freelancer_django
python -m venv venv
.\venv\scripts\activate.bat
pip install -r requirements.txt
```
If you need to run DB migrations:
```
python manage.py makemigrations
python manage.py migrate
```
Now, run the project.
```
python manage.py runserver
```