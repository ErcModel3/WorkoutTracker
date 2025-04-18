# Fitness 💯

The final outcome of this project is to create a gym workout tracker / planner that will allow signed-in users to:
* Use and create new exercises to log
* Log the exercises, weights and reps in workouts
* Use and create new workout templates

This project will use supabase as a database but will make use of abstraction between the framework and the database backend so the database provider could be swapped over to firebase at a later date.

When development has worked using cloud solutions I'd like to expand on this by running the app as seperate services on-prem, making use of the EaC (Everything as code) model and implementing DevOps pipelines where possible.

The tech stack for this program will be comprised of Flask, PostgreSQL via Supabase and hosted / deployed on Vercel to the be hosted on my own server and buliding a suitable dev, uat and prod deployment states.


# Development
To install and run the development server, you'll need to:
* create a new virtual environment
```python3 venv (name of virtual environment)```
* enter / activate the venv in your workspace
```source path-to-venv/bin/activate```
* install all requirements
```pip3 install -r requirements.txt```

To exit the venv use command:
```deavtivate```

To actually run the development server, you'll need to use the command:
```flask --app main run```
Which will start the development server on localhost:5000
