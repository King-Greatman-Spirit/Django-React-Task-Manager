# Django-React-Task-Manager

A Task Manager application created in React as the  client-side and Django Rest Framework as the server-side

React in a nutshell, is a JavaScript library that is great for developing single page applications (SPA) and it has solid documentation if you're interested tor read about React.

So React serves as the front-end , handling UI through the requests to Django's; which serves as the backend.

The prerequistes for this project are 2 essential elements:

1- Python 3, obviously [ prefereably 3.5 and above] 

2- Node.js - you can install node from nodejs.com and download it very easily, and you can check it if it was properly installed or not : node --version

And we are going to start by our favorite side which is the backend , I'm saying our favorite side because this channel focuses on server-side programming and mainly Python.

# Installation guide
git clone https://github.com/King-Greatman-Spirit/Django-React-Task-Manager.git

#Setup Backend
1. cd Django-React-Task-Manager/backend
2. virtualvenv # Create a virtual environment
3. source venv/bin/activate # Activate venv on macOS.
4. source venv/Script/activate # Activate venv on windows.
5. pip install -r requirements.txt
6. python manage.py createsuperuser
7. python manage.py runserver

#Setup Frontend

1. cd Django-React-Task-Manager/frontend
2. npm install
3. npm start
