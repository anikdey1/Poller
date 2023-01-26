# Poller
A basic application that allows users to take part in polls.


## Motivation
I used this to learn the basics of [Django](https://docs.djangoproject.com/en/4.1/intro/tutorial01/).

## Pre-requisite Tools
The following tools are needed to run this application:
- [Python](https://www.python.org/downloads/)
- [Django](https://docs.djangoproject.com/en/4.1/intro/install/)
- [Python Decouple](https://pypi.org/project/python-decouple/)


## Instructions
To run the application locally on Windows, follow these steps:

1. Clone the repository onto your machine.
2. Open Command Prompt and navigate to the project folder.
3. Create a `.env` file using this command: `type nul > .env`
4. Open the `.env` file with an editor, and place the secret key in it, using the following format: `SECRET_KEY = '<SecretKey>'`
5. Enter the following command to run the local server: `py manage.py runserver`
6. Add the following slug after the localhost URL provided by the previous command to open the app: `/poller`
7. Use the `/admin` slug to access the administration site.
