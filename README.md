flask-skeleton
==============

## A Flask skeleton app to get you started

Flask-Skeleton makes use of a few Flask plugins: 

* Flask-Bootstrap 
* Flask-SQLAlchemy 
* Flask-Script

You can check them out the full list in the [requirements.txt](https://github.com/Shidima/DrunkTurtle.com/blob/master/requirements.txt). This app template is based for a large part on the work [Miguel Grinberg](http://blog.miguelgrinberg.com/) did for his book [Flask Web Development](http://flaskbook.com/). If your new to Flask I sugest you check it out, it's a very good intro to Flask. I made this skeleton app so I would have a good base to start my next Flask app from. 

To get started you need to install Python, pip and virtualenv. If you have these installed run the following inside the **flask-skeleton** directory:

```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt 
```

This will setup the required dependacies for flask-skeleton. After that you can run 

```
python manage.py runserver
```

to get started.