# Module E9.
## Subject: Flask application

This application implements an event scheduler.

This application uses Flask as the framework for the application, celery for queuing and PostgreSQL for data storage.

To run the application on a local machine, you need:


* clone this repository
* go to the folder by the repository
* Run the command docker-compose up -d on the command line
* After the command is successful, the application is launched at 127.0.0.1:5000 with the following endpoints:

* / create_user - registration of a new user
* / login - login form (to log in, you must first create a user)
* / schedule, / - summary of all existing events
* / event - create a new event
* / event / <id> - updating an existing event, where <id> is its identifier. You can also get to this page from the list of events. You can edit only "your" events.
