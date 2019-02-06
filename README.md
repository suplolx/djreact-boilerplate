# Usage

Simply clone the repository to your local workspace

```
git clone https://github.com/suplolx/djangorestframework-boilerplate.git
```

Create **and activate** a virtualenv (optional)

```
virtualenv venv
```

Install the requirements

```
pip install -r requirements.txt
```

Migrate database migrations

```
python manage.py migrate
```

Install node modules

```
npm install
```

Build static files

```
npm run dev
```

Run the server!

```
python manage.py runserver
```

Browse to http://localhost:8000 on your local machine

# Includes

- Django v2.1.2 (https://www.djangoproject.com/)
- Django REST framework v3.8.2 (https://www.django-rest-framework.org/)
- Django CORS headers v2.4.0 (https://github.com/ottoyiu/django-cors-headers)
- Django rest Knox