# GCI-Django-Hello-World
Made for the sole purpose of GCI 2019

### Open GCI(folder) for application files

  ## ___Setting Up Django framework for python on Linux:___


 ### _Installing Django:_
  
  1) Python must be installed
  
  2) Open terminal and go to the root directory
        
3) Install the python package repository(PyPi) the pip tool(one time only) if not installed already.
  
  ` $ sudo apt install python3-pip`
      
4) Install python virtual environment

`$ pip install virtualenv`

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resouurces/Screenshot%20from%202019-12-21%2014-25-00.png)
      
5) Create and select a directory for your project

` $ mkdir project`	

 `$ cd project`
 
6) Creating virtual environment(one time only)

`$ virtualenv django`

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resouurces/Screenshot%20from%202019-12-21%2014-26-24.png)

7)install django

`$ pip install django`

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resouurces/Screenshot%20from%202019-12-21%2014-29-02.png)

### ___Creating and working on the project:___

1) Continue in the same terminal

`$ django-admin startproject projectname`

2) Open the directory in which the above statement was passed		
  
3) Create a views.py file as attached and edit the urls.py file as attached, make sure views.py is one folder outside the directory of urls.py
  
4) Run the server locally on the prompt

`$ python manage.py runserver`   (make sure the current directory is the directory which hold manage.py)

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resouurces/Screenshot%20from%202019-12-21%2014-34-33.png)
  
5) Type http://127.0.0.1:8000 in your web browser, your content would show up.

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resouurces/Screenshot%20from%202019-12-21%2014-33-30.png)
