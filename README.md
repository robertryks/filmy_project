# filmy_project
baza danych w postgresql zainstalowana przez homebrew i ustawienia settings.py:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'kurs_django',
        'USER': 'postgres',
        'PASSWORD': 'postgres',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}

oprócz zainstalowania venv i django (4.05) potrzebne paczki:
psycopg2
Pillow

potem superuser i zabawa.
