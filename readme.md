### SAVINGS APP API

#### Base Technologies

| Technology | Version |
| ---------- | ------- |
| DJANGO     | 4.1.7   |
| pip        | 23.0.1  |
| PostgreSQL | 14.x    |

##### Main Packages

| Packages            | Role           |
| ------------------- | -------------- |
| djangorestframework | API Web Server |
| JWT                 | API Encryption |

### API Requirements

- Python3 version 3.10 and above Installed
- PostgreSQL Installed

### Getting started.

- Clone the repo from Gitlab.
- Create Postgres Database.
- Import Init Db run `pg_restore -U postgres  -d  saving_app  saving_app.dump` from the root directory
- Update the necessary environment variables in the settings.py file.
- create a virtual env for the project dependencies
- Install dependecies with `pip install -r requirements.txt`.
- To run the app run `python manage.py runserver`.
- Set nginx or apache to serve static files for production
- The your app will be runing on port 8000
