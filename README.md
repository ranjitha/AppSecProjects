# AppSecProjects
This blog web app is known as the Bikini Bottom blog used by spongebob characters. It allows for creating users and users can post onto the blog. The web app is vulnerable against CSRF attacks because it uses a really weak non-random secret key which is 'key' and has weak authentication. All that is need is the correct email and password of the user to login and and there is unlimited attempts to log in. On top of all of this the database stores the passwords in unhashed. This means the passwords are in plaintext in the database so if someone gains access to the database, they can see all of the users and their passwords.

# Dependencies
Needed Libraries to Run:
Pip install flask
Pip install flask-login
Pip install flask-sqlalchemy
Pip install flask-bcrypt
Pip install flask-wtf

# How To Run
Run run.py in the terminal and navigate to the localhost on your system to view the web app.
