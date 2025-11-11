## Settings
    python=3.11.9

## Clone project
    git clone https://github.com/nilrey/django.git
    continue from the root directory, means on the same level with manage.py
    create venv 
        python -m venv venv
    run venv
        .\venv\Scripts\activate
    import dependences from requirement.txt 
        pip install -r requirement.txt
    install database
        python manage.py migrate
        python manage.py createsuperuser
        python manage.py collectstatic

## Run server
    .\venv\Scripts\activate
    python manage.py runserver