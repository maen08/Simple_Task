# Simple_Task
Assigned to build a To-do app API with these features:
- Register user 
- Login user
- User can create a task
- User can view all the tasks
- User can categorize tasks (add task into a group)
- List all user

## Install the project
- Clone a repo and install all dependencies
```
$git clone https://github.com/maen08/Simple_Task.git

$cd Simple_Task

$pip install -r requirements.txt 
```

## Run the project
```
$ cd todo_app
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py runserver
```

- Project will be running on 127.0.0.1:8000


## Endpoints
API Endpoints:

- /user              => shows all registered users
- /accounts/signup   => signup endpoint 
- /accounts/login    => login endpoint
- /                  => list all tasks
- /admin             => admin page (create a super user to login as admin)


## 