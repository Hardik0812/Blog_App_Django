# Blog_App_Django


BlogApp
1. create, delete, update profile
2. create , update , delete, read blogs
3. pillow used for image storage
4. add comment, delete comment (Authenticated Users Only)



## Install Dependencies
pip install -r requirements.txt

## Development server

Run `py manage.py runserver` for a dev server. Navigate to `http://localhost:8000/`. The app will automatically reload if you change any of the source files.

## Set Database (Make Sure you are in directory same as manage.py)
python manage.py makemigrations
python manage.py migrate

## Create SuperUser
python manage.py createsuperuser

After all these steps , you can start testing and developing this project.