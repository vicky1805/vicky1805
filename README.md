
Mcq-Web-App
A Python Django web application for taking MCQ (Multiple choice questions) tests.

About
This application is developed in Python Django (a web framework for rapid development). A user can sign in with any of the one roles "Moderator" or "Contestant". for more info see roles below. This Web Application presents a set of random questions from database to user and calculates user score accordingly.

Types of User-Roles (Roles)
Moderator: A user who wants to take tests. Contestant: A user who gives tests.

Features
Contestant Exam State Tracking.
Contestant Login and SignUp.
Admin Panel.
Score Calculation Rules.
Moderator can take multiple tests.
Moderator can assign any number of test that he has designed to any number of some students.
Setup in production environment:
This application is currently in development phase and hence its not suitable to use it in production environment till then you can try this application on your local machine see intructions "Run on local machine" Once its release of first version it can be used in production.

Run on local machine - instructions
pip3 install virtualenv
export PATH=$PATH:~/.local/bin
virtualenv -p python3 my_virtual_env
cd my_virtual_env
source bin/activate
(my_virtual_env) $ git clone https://github.com/ankity10/Mcq-Web-App.git
(my_virtual_env) $ cd Mcq-Web-App
(my_virtual_env) $ pip install -r requirements.txt
(my_virtual_env) $python manage.py runserver 8080
Open this link -> localhost:8080 and try this application.
Todo
Import questions from excel sheet.
Ability to select questions for each test.
Ability to select students for each test
Ability to set marking scheme for each test.
Contributing
You can setup this project locally by following intructions given above.
Then after fixing any issue yo can do a pull request.
In case of any issues please contact me => ankitwrk at gmail
