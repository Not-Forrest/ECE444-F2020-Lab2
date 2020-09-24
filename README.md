# Forrest Zhang
This repo is a clone of https://github.com/miguelgrinberg/flasky

# Activity 1
![task1](/screenshots/Task1.png)

# Activity 2
![task2](/screenshots/Task2.png)

# Activity 3

Flask uses context globals to allow functions to treat certain variables as global, but in reality these variables are thread-specific.
The context globals are:

Variable| Context| Description
--- | --- | ---
current_app| Application | The application instance for active application
g | Application  | Temporary storage variable PER application instance. Reset per request
request | Request | Content of request sent by client
session | Request  | User session, stores values between requests
