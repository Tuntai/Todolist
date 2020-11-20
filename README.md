# Todolist
A user friendly Todo App built using Django, with the functionality of color coding tasks using different catogories.

# How will it look?
![Screenshot1](media/Basic.png)
![Screenshot2](media/adding_task.png)
![Screenshot3](media/adding_date.png)
![Screenshot4](media/multipletasks.png)

## To run this web-app in your local systems:

### 1. Pre-requisites:
1.Python 3
2.pip 3
### 2. Clone this Repo :
```sh
git clone https://github.com/Tuntai/Todolist.git
cd Topic-Tracker-Model
```
You can also download the folder and extract all the files in your local system.
### 3. Apply migrations : 
```sh
python manage.py makemigrations
python manage.py migrate
```
### 4. Run server:
```sh
python manage.py runserver
```

#### Change the categories according to your preferences by creating a superuser 
```sh
python manage.py createsuperuser
```
