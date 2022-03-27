# Polarcape APIs project
- --
### This is my solution to the email sent task by Polarcape, I chose *flask* as the framework and *SQLite* as database. 

### Repo contains:

- app.py (where models and apis live)
- database.db (dummy database file I used) 
- pc-test (postman collection for testing)
- requirements.txt (dependency list file)

### How to run it:

You need to have python 3.7 and Postman(optional) installed.
Then just clone this repo, open it in your IDE and install requirements by running:

```
pip install -r requirements.txt
```

To run the app just press the run button on your IDE,
or if you don't have an IDE just run:

```
flask run
```


I recommend you use Postman to test the API endpoints, it's test collection is part of this repo and it will save you time.
All you need to do is import it in your Postman run *app.py* and send the requests. Please note that Postman will send requests at *localhost:1000*
if you run the server differently please make the appropriate changes.  

### Thank you.

