# Application Security Assignment 2
This blog web app is known as the Bikini Bottom blog used by spongebob characters. It allows for creating users and users can post onto the blog. The web app is vulnerable against CSRF attacks because it uses a really weak non-random secret key which is 'key' and has weak authentication. All that is need is the correct email and password of the user to login and and there are unlimited attempts to log in. In addition, the database stores the passwords unhashed. This means the passwords are in plaintext in the database so if someone gains access to the database, they can see all of the users and their passwords.

## Dependencies
Needed Libraries to Run:
```bash
pip install flask
pip install flask-login
pip install flask-sqlalchemy
pip install flask-bcrypt
pip install flask-wtf
pip install pillow
```

## How To Run
1. Ensure the required libraries are installed as listed above. 
2. cd to (your) correct directory with the provided code.
3. Run run.py in the terminal and navigate to view the web app.
4. Go to local host specified in program output using your browser (should be local host with IP address http://127.0.0.1:5000/)

## Contribution
This project was done in collaboration with Ranjitha Gurushanthappa.
