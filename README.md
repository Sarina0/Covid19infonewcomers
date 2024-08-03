# Python-Firebase-Flask web-app for newcommers

## Features
1) Login/Sign up - Hosted on Firebase
2) Fully responsive UI
3) Based on Python-Flask

## Requirements
```bash
pip install pyrebase4
pip install flask
```

## Setting up Firebase

1) Go to https://console.firebase.google.com
2) Login/Register your account
3) Click on add project
4) Give the project name
5) Optional: select google analytics
6) Create a project
7) Under "Get started by adding Firebase to your app", click on web app
8) Name the web app and copy the "apiKey", "authDomain", "databaseURL", "storageBucket" from the code given there
9) Go to main.py and add the values you copied above
10) Go to console, click on authentication (On the left sidebar), click on sign-in method, and enable email/password sign in
11) Go to Storage (On the left sidebar), and click on "Create Database", start in test mode for now, click done.
12) You are all set on firebase !!!

## Additional Info

The server starts by default on http://127.0.0.1:5000/
After successful sign-up, the user name, email,and uid are stored in a global dictionary called person
# link to hosted web
Here is the [link](https://covidweb-flask.onrender.com/) to the Web Application. 
- Please be patient as it takes at least 1-2 minutes for the page to load!
### Please let me know if you have any questions on Discord :)! sarina7426
