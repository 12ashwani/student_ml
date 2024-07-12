## End to end ml project and deployment
How to create ML model and deploy ML model
* 1- Firstly create a folder then open the folder in Vs code or any other IDE
* 2- Create a new environment using conda command or other command
   *  A-First, check if the environment myenv exists by listing all available environments:

# conda info --envs
* B-If myenv does not exist, you can create it using the following command:
# "conda create --name myenv python=3.8"


 # A-'conda create -p myenv python==3.11.0' Use this command in terminal to create an environment for conda
* 3- Activate the environment
# A- "conda activate environment_name/" in my case my environment is "conda activate D:\ml-project\new_ml_project\myenv"
* 4- Creating new git hub repository in Github then using the below line of command for model deployment
in git hub repository
* 5- Creating README.md file inside your project folder
Then push this file to github repository using the below command
*Create a new repository on command line*
echo "# my_new_project" >> README.md
* git init
* git add README.md 

* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/12ashwani/student_ml.git
*  

* 6- Create file in github repository to skip unnecessary data or file ".gitignore" file extension "python" and commit
Put environment file neme inside gitignore file to keep environment file safe
* 7- Run "git pull origin main" command to import the file from repository to project
* 8- Create new file inside project folder "requirements.txt" Inside the file write some library name which library you have used in whole project
* 9- Run "pip install -r requirements.tsxt" command in terminal to install required library so that important package or library can be installed in environment
* 10- Create new file "setup.py"
* a- Create src folder and create __init__.py file in src folder
* b- Inside setup.py file you can define the whole setup of your project in this file
To execute this file you can run "python setup.py install" command
* 11- Create a template file to create project template of a project,
Inside this file you can define the project structure
* 12-This module defines functions and classes which implement a flexible event logging system for applications and libraries.

# The key benefit of having the logging API provided by a standard library module is that all Python modules can participate in logging, so your application log can include your own messages integrated with messages from third-party modules
* 13- Write code inside the exception.py and logger.py
* 14- Create a file .env for facthing the all information regarding to data base
* 15 - Write a code int the utils.py for connection



# DVC COMANDS
* 1-dvc init
* 2- dvc add artifacts/raw.csv
* 3- git add artifacts\raw.csv.dvc
* 3- git add artifacts\.gitignore
