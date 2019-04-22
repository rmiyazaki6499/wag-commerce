# wag-commerce project - Skypiea Store
E-Commerce Site using Django, Wagtail and Snipcart

To execute this project you will need Python 3.
Download it here:
https://www.python.org/downloads/

Once you have Python you will need pip which is a package installer to download all necessary libraries and frameworks of the project.
Installation directions are here:
https://pip.pypa.io/en/stable/installing/

Once you have Python 3 and pip you will be able to download packages. 
The first package to download will be pipenv to manage our libraries and dependencies. 

In your terminal type the commands:
``` $ pip install pipenv ```
This will install pipenv. 

Once downloaded go to your project directory and type in the commands:
``` $ pipenv shell ```

This will create a pipfile as well as a pipfile.lock which will keep all of your dependencies for the project.
It will also initiate the virtual environment for you to isolate your project from any global dependencies. 

Once you are in the virtual environment we will download the necessary frameworks.
First let's download Django using:
``` $ pipenv install django ```
This will install Django

Next let's download Wagtail:
``` $ pipenv install wagtail ```

