btre_resources

1. Run venv `source /Applications/Projects/btre_resources/venv/bin/activate`
2. Start project `python3 manage.py runserver`
3. Regenerate static files `python manage.py collectstatic`
4. Generate new folder `python manage.py startapp contacts`
5. Make sure to add to btre (main folder) / urls.py for central routing

When using `models.py` for DB:
1. Make migrations `python manage.py makemigrations`
2. Migrate `python manage.py migrate`
3. admin.py - to setup how the data is displayed on the admin panel

1. urls.py - handles URL structure
2. views.py - handles how one networks request will run