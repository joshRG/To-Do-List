# ***To-Do-List***
<sup>A web app developed in django to make simple TODO lists</sup>

- [Sample View](#Sample-view)
- [How it Works](#how-it-works)
- [Prerequisites](#Prerequisites)
- [Getting started](#Getting-started)

## [Sample View](#Sample-view)

    Login View
![image](https://user-images.githubusercontent.com/32374996/204930341-1b5c418a-c7c1-4c2c-a46a-28927175874c.png)

    Tasks List View
![image](https://user-images.githubusercontent.com/32374996/204930686-0b0e21fd-2e94-42e1-ae63-ca9a3e934b22.png)

    Delete Confirmation View
![image](https://user-images.githubusercontent.com/32374996/204930787-cd82b510-7c51-42b6-9e93-4def59e5bb80.png)

    Task Creation View
![image](https://user-images.githubusercontent.com/32374996/204930902-ee3836ce-12cf-4795-bfe8-0e8a8ea3169f.png)



## [How it Works](#how-it-works)
Web app based on python's framework, django. 

The web page is developed with an aditional app, named base, where all the operations takes place and a simple model related with a FK of the User model that django make since the first command that start the project, allowing this the feature to separate tasks by users so they'll not be able to see other's items. With class based views the correct rendering of the wished forms are easy to handle from there we can easily inherit from the imports and django principle libraries such as "render", "reverse_lazy", "LoginRequiredMixin" and others used in the project for features like the user registration form and the login validation logic.

The web page used as front end html and css, where the main.html has all the style and the other files.html inherit from it the configurations.

    Guide through the runing project

With all these said basically you hop on the link given you in the console runing in the server executed by django with the manage.py and the first you're going to see is the login view where you'll have to create a user in the "register" section. 

After that its going to automaticly log you in and you would be able to create in the plus sign items to complete or items that you may have already completed. 

Clicking in the title of the task you'll be able to edit it as its sends you to the creation form. 

With each cross next to the items or task you could delete the item.

With the logout part you could just leave that account and enter another.


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
    
