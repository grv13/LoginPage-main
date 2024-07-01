# Web App
# Live link for web app
https://web-app-xdvb.onrender.com/

## Introduction
This Flask application is designed to handle user authentication, including user login, signup, and logout. It uses Flask Blueprints for modular organization and follows best practices for security by hashing user passwords.

## Table of Contents
Installation
Configuration
Usage
Routes
/login
/signup
/logout
Dependencies
Contributing
License
Installation
Clone the repository:

bash
Copy code
git clone <repository_url>
cd <repository_directory>
Install the required packages:

bash
Copy code
pip install -r requirements.txt
to update :
pip freeze > requirements.txt
Set up the database:

Ensure that the database is configured in the __init__.py file.
Run the following commands in the terminal:
bash
Copy code
flask db init
flask db migrate
flask db upgrade
Configuration
Database Configuration:

Open the __init__.py file and update the database configuration.
Make sure to set the correct database URL.
Secret Key:

Open the __init__.py file and set a secure value for the SECRET_KEY.
Usage
Run the Flask application:

bash
Copy code
python run.py
Visit http://localhost:5000 in your browser to access the application.

Routes
/login
Method: GET, POST
Description: Allows users to log in.
GET: Renders the login page.
POST: Validates user credentials and logs in if successful.
/signup
Method: GET, POST
Description: Allows users to sign up for a new account.
GET: Renders the signup page.
POST: Validates the signup form, checks for existing emails, and creates a new user if successful.
/logout
Method: GET
Description: Logs out the currently logged-in user and redirects to the home page.
Dependencies
Flask
Flask-Login
Werkzeug


 
![logo](https://github.com/grv13/LoginPage-main/assets/118931467/aaac9655-af61-4d10-a569-4cd8e382280d)
