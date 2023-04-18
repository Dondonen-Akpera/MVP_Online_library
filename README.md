# MVP_Online_library

This is a web application that creates on online catalog for a small local library, where users can browse available books and manage their accounts. It was developed using python and django framework. To get the project up and running locally on your computer, you will have to set up Python Development Environment, preferrably Python 3.10.11. Enusre to use a virtual environment.

# Steps to set up the project

Assuming you have python setup, run the following commands to create and admin account and get the server up and running

pip3 intall -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

After running the commands, open your browser, visit http://127.0.0.1:8000/admin/ to open the admin site and http://127.0.0.1:8000 to open the main site.

The main features that have currently been implemented are:
1. There are models for books, book copies, genre, language and authors
2. There are two active users of the web application; Librarian (Admin) and Readers
3. Admin users can create and manage models. They can also create new books, authors and renew dates for borrowed books
3. Users can view list and detail information for books and authors
4. Users can login and logout using their account details

