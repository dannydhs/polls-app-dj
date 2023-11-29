# Polling application
python=3.8.10 | django=4.2.7

Basic poll application.
- Public site that lets people view polls and vote in them.
- Admin site that lets you add, change, and delete polls.

## Create virtual environment
```sh
python3 -m venv .venv
```

## Install Dependencies
```sh
pip install -r requirements.txt
```

## Apply Migrations
```sh
python manage.py migrate
```

## Create Admin User (for django admin)
```sh
python manage.py createsuperuser
```

## Run Project
```sh
python manage.py runserver
```