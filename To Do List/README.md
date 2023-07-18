This project is built from a tutorial on building a CRUD app with Python/Flask:
https://pythonistaplanet.com/flask-to-do-list/

Run the application and navigate to the address provided:
```bash
flask run
```

The FLASK_APP is set to app.py by default. FLASK_ENV can be set to development if not already.
The templates folder contains the base.html file (which contains the boilderplate code),
and the index.html(which contains the content to be displayed on the web page).
The static folder contains the css folder and the style.css file. This file is linked to the base.html file:
    style.css > base.html > index.html > app.py

For the database, SQLAlchemy is utilized as the ORM (object-relational mapper), and SQLite as the database.
To create the database, type ```python``` in the terminal, and the following:
```bash
    from app import db
    db.create_all()
    exit()
```
