step1: install and activate virual env
windows:
    installment :pip install virtualenv 
    creation :virtualenv <name> 
    activation :source <name>\Scripts\activate -make sure it's active when ever your're working on the project  
ubuntu:
    installment :sudo apt install python3-venv python3-full -y 
    creation :python3 -m venv <name> 
    activation :source <name>/bin/activate -make sure it's active when ever your're working on the project  

step2: install django and packages
pip install django
pip install pillow

step3: start with django
django-admin startproject blog_main .
python manage.py runserver
python manage.py migrate
python manage.py createsuperuser

step4:create templates
step5:create static files

step6:create blogs and categories 
python manage.py startapp blogs
go to setting.py and add to installed_apps
add to model.py
python manage.py makemigrations
python manage.py migrate
register the model in admin.py


step7: handle media
add media_url in setting.py
add to url.py
create media files at root


1:36:30 - https://www.youtube.com/watch?v=1-1ePcEDcqI

