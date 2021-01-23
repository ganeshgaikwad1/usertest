# usertest

Follow following steps:

  1.create an environment 

 Create a project folder and a venv folder within:

	- mkdir myproject
	- cd myproject
	- python3 -m venv venv
	-virtual flask_env

    2.Activate the environment

 Before you work on your project, activate the corresponding environment:
	
	-> venv\Scripts\activate

 Your shell prompt will change to show the name of the activated environment.


   3.Install Flask
 Within the activated environment, use the following command to install Flask:

	- pip install Flask

 Flask is now installed. Check out the Quickstart or go to the Documentation Overview.

	4.Create db in flask

	-flask initdb
        -Initialized the database.
	
	5.Flask-Migrate

  Flask-Migrate is an extension that handles SQLAlchemy database migrations for Flask 
  applications using Alembic. The database operations are provided as command-line
  arguments under the flask db command.

 You can then generate an initial migration:
	- flask db init

 Then you can apply the migration to the database:
	-$ flask db upgrade

 To see all the commands that are available run this command:
	
	-$ flask db --help

