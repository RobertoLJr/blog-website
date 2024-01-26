# Day 71 Project: Website's Blog Deployment

## Concept

This program is the actual implementation of [Day 71 Project: Website's Blog Deployment](https://github.com/RobertoLJr/100-days-of-python/tree/main/day-071-project-web-application-deployment), deployed in the Cloud
application hosting for developers [Render](https://render.com/) with a free tier account.
It functions as a blog with an internal database
for storing users, posts, and comments.

Please note that the free instance types will spin down with inactivity within Render,
and that the database will expire after April 24, 2024. After that date,
this project might not function as per expected in its deployment,
however, the files will still be available for migration.

You can see the website here: https://websites-blog-deployment.onrender.com/

## Resources

### Engines/Frameworks/Modules

- [CKEditor](https://flask-ckeditor.readthedocs.io/en/latest/) - Integration of CKEditor for Flask.
- [Flask](https://flask.palletsprojects.com/en/3.0.x/)
- [Flask-Login](https://flask-login.readthedocs.io/en/latest/) - Provides user session management for Flask.
- [FlaskWTF](https://flask-wtf.readthedocs.io/en/1.0.x/) - Integration of Flask and WTForms.
- [Gunicorn](https://gunicorn.org/) - Python WSGI HTTP Server for UNIX.
- [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
- [psycopg2](https://pypi.org/project/psycopg2/) - PostgreSQL database adapter for Python.
- [SQLAlchemy](https://www.sqlalchemy.org/)
  - [SQLAlchemy Basic Relationship Patterns](https://docs.sqlalchemy.org/en/20/orm/basic_relationships.html)
- [Werkzeug](https://werkzeug.palletsprojects.com/en/3.0.x/) - Used in this project to handle password hashing.
- [WTForms](https://wtforms.readthedocs.io/en/3.0.x/)

### Services

- [Render](https://render.com/)
- Others: [Heroku](https://www.heroku.com/home), [Cyclic](https://www.cyclic.sh/), [Glitch](https://glitch.com/), [Vercel](https://vercel.com/), [PythonAnywhere](https://www.pythonanywhere.com/)

### Miscellanea

- [Creating or using requirements.txt](https://docs.google.com/document/d/e/2PACX-1vRIW_TuZ6z0ASjAoxgJgmzjGYLCDx019tKvphaTwK_Za7fnMKywUuXI0-s5wr0nQI_gprm6J6y7L9rL/pub)
- [DB Browser for SQLite](https://sqlitebrowser.org/) - Useful for visualizing databases' structures and data.

### Additional reading

- [PEP 3333 - Python Web Server Gateway Interface (WSGI) v1.0.1](https://peps.python.org/pep-3333/)