## Getting started with development

Dependencies:

- Python 3.6.x
- Django 1.11.x

### 1. Install python packages

```bash
pip install -r requirements.txt
```
### 2. Run database migrations

```bash
cd <App Name>
python manage.py migrate
```

### 3. Create superuser

```bash
python manage.py createsuperuser
```

### 4. Run development server

```bash
python manage.py runserver
```