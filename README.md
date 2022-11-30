# ***To-Do-List***
<sup>A web app developed in django to make simple TODO lists</sup>


- [How it Works](#how-it-works)
- [Prerequisites](#Prerequisites)
- [Getting started](#Getting-started)


## [How it Works](#how-it-works)
Web app based on python's framework, django. 

The web page is developed with an aditional app, named base, where all the operations takes place and a simple model related with a FK of the User model that django make since the first command that start the project. With class based views the correct rendering of the wished forms are easy to handle from there we can easily inherit from the imports and django principle libraries such as "render", "reverse_lazy", "LoginRequiredMixin" and others used in the project for features like the user registration form and the login validation logic.

The web page used as front end html and css, where the main.html has all the style and the other files.html inherit from it the configurations.


## [Prerequisites](#Prerequisites)
    Python = 3.10+
    django = 4.1.3
    sqlite
    Pipenv
    
    
## [Getting started](#Getting-started)
    Install Python 3.10 or later versions
    Install Pipenv
    Install SQL or SQLlite
    Download the project
    With VScode in the project folder, with the vscode build in terminal, run  "pipenv shell"
    With VScode in the project folder, with the vscode build in terminal, run "pipenv install *" (this will install all in the pipfile in a virtual enviroment)
    With VScode, with the build in terminal, run the command "python manage.py makemigrations"
    With VScode, with the build in terminal, run the command "python manage.py migrate"
    With VScode, with the build in terminal, run the command "python manage.py runserver"
    
