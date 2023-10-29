# drones_shop

Let's start from linking to db postgresql. 

1.download postgresql on your machine by link(https://www.postgresql.org/download/) and set up.
2.For view db use the tool DBeaver

To connect to the postgresql use this options:
3. pip install psycopg2
4. DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'db_name',
        'USER': 'your_username',
        'PASSWORD': your_password
        'HOST': 'localhost',
        'PORT': '5432'
    }
}
