**Online Course App**

This app is built in django as a side project. It provides learners to enroll in different courses and take lessons and exam assessments related to that particular course. Also, Instructors can create lessons and provide multiple choice questions for the course to be used for grading in course assessments exam. This app also uses **django-admin** feature to provide an admin panel to perform CRUD operations on courses,learners,instructors and questions.

**Tech Stack**

--Django
--SQLlite3
--HTML/CSS
--JavaScript
--Bootstrap

**Installation**

- Make sure you have installed python 3.11 or above to run this project.
- for admin panel: username=admin,password=password@123
 
*-Environment Setup-*
1. Clone the repo from github using git clone command.
2. After cloning open repo in your IDE (i.e: VS Code).
3. Run ".venv/Scripts/activate" command in terminal of IDE (run this command only if you want to run the project in virtual environment -preferable)
3. Run pip install django pillow and pip install -U -r requirements.txt sequentially.
4. After installation, execute following commands one by one:
   1. py manage.py makemigrations
   2. py manage.py migrate.
   
*-Run Website-*
1. Run following command in terminal to run website:"py manage.py runserver"
2. Your application will run in browswer on following url: http:localhost:8000/onlinecourse/


**ER Diagram**
For your reference, we have prepared the ER diagram design:.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)
