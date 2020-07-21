## Django-Blog-Website-Learning-
Blog Website

This is My Django based Blog Website where one can WRITE/READ Blogs , make comments and can connect to various social media Website.

## Instructions
  ### 1.Installations

        Make sure to have python version 3 install on your system.

        Clone repository

        git clone https://github.com/mohitmp9107/Blog-Website-Django

        cd Blog-Website-Django

  ### 2.Install Dependencies

        pip install -r requirements.txt

  ### 3.Migrations
        Run

        python manage.py makemigrations

        python manage.py migrate

  ### 4.Create superuser
        To create super user run

        python manage.py createsuperuser

        After running this command it will ask for username, password. 

        You can access admin panel from localhost:8000/admin/

  ### 5.Run Locally
        python manage.py runserver

        Run at localhost. It will be on port 8000 by dafault.

