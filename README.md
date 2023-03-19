# ChatApp

## Steps to start the application

Chat Application using Django REST Framework and PostgreSQL

Install virtualenv
```
pip install virtualenv
```

On the project directory, create a virtual environment
```
virtualenv chatSystem
```

To activate virtual environment
```
source chatSystem/bin/activate
```

To deactivate virtual environment
```
deactivate
```

Install requirements
```
Requirements consists of:
Django==2.0
django-widget-tweaks
djangorestframework
psycopg2-binary
pytz

pip install -r requirements.txt
```

If needed please do database migrations
```
python3 manage.py makemigrations
python3 manage.py makemigrations chat
python3 manage.py migrate
```

Run dev server
```
python3 manage.py runserver
```

You might face error such as 
```
AssertionError
Exception Value:	
database connection isn't set to UTC
```
You might have to comment out 
```
if offset != 0:
        raise AssertionError("database connection isn't set to UTC")
```


## Login and Register

![](https://user-images.githubusercontent.com/55325635/226153980-f5fdf31c-db62-4615-aae9-243332e3aae9.png)

![](https://user-images.githubusercontent.com/55325635/226153988-93d21885-9f81-47f8-aae3-9b4a70273a0b.png)

## Chat System

![](https://user-images.githubusercontent.com/55325635/226154085-71c16e2e-e9a0-4509-abe5-fbc35750deef.png)


![](https://user-images.githubusercontent.com/55325635/226154083-1dfb29b0-5959-4b4b-a22d-e8169170f2b9.png)
