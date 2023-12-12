# CRUDClicker_backend
Setup:

1. Create a project folder for Django by creating a virtual environment. To installed virtualenv package.
     1. python -m pip install --user virtualenv
        
2. create Virtual enviroment
     1. python -m venv env
     2. cd env
     3. Scripts\activate
        
3. Run requirments.txt file
     1. pip install -r requirements.txt
        
4. pull quotes folder from github and place inside of env folder
5. To detect changed made to the DB run: "python manage.py makemigrations"
6. To apply chages to DB run: "python manage.py migrate"
7. To run server run: "python manage.py runserver"
   server should be running at localhost:8000/wel/
