# TITLE: AGROCULTURE

# DESCRIPTION: Agroculture is a user-friendly platform that connects customers with farmers, offering a seamless shopping experience for agricultural products. Customers can browse, search, and securely purchase items, while farmers manage their profiles and listings efficiently. The platform also features a feedback system for transparent communication between customers and farmers, enhancing trade and user satisfaction.

# GETTING STARTED

1. Ensure python is installed on your system. If not, download the latest version from https://www.python.org/downloads/. During installation, please remember to check the "Add to Path" box.

2. Then, use pip to install these dependencies in a terminal:

	pip install django==3.0.5
	pip install django-widget-tweaks
	pip install xhtml2pdf

3. Navigate to the agroculture folder in the terminal and apply the following migrations:

	python manage.py makemigrations
	python manage.py migrate

4. Now, start the Django server by running 

	python manage.py runserver

5.  To start using the application, open a browser and enter http://127.0.0.1:8000/ 

# USERS

# Farmer

- To create farmer login we will run the following command in the terminal
	python manage.py createsuperuser
- Give username, email, password and farmer account will be created. 

# Customer

- To create customer account first sign up (don't forget to add a picture). 


# TECHNOLOGY STACK
- HTML5
- CSS
- Javascript
- Python || Django
- jQuery

# FOLDER STRUCTURE: 

# agroculture
    - ecommerce - Main directory of our project, where Django project files are stored.
    - static - contains image files
    - templates - contains html files
    - db.sqlite3 - SQLite database file where data for our Django project is stored.
    - manage.py - This is a command-line utility that lets us interact with our Django project. 
    - requirement.txt - lists all the Python dependencies required by our Django project.

