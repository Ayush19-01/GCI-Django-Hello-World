# GCI-Django-Hello-World
Made for the sole purpose of GCI 2019

Open Hello(folder) for application files

  ___Setting Up Django framework for python on windows:___


  _Installing Django:_
  
  1)Python must be installed
  
  2)Open command prompt and go to the root directory
        
3)install the python package repository(PyPi) the pip tool(one time only)
  
  `-->python -m install -U pip`
      
4)install python virtual environment

`-->pip install virtualenv`

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resources/1.PNG)
      
5)create and select a directory for your project

`-->md project`	

 `-->cd project`
 
6)creating virtual environment(one time only)

`--> virtualenv django`

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resources/2.PNG)

7)install django

`-->pip install django`

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resources/3.PNG)
___Creating and working on the project:___

1)continue with the command prompt

`-->django-admin startproject projectname`

2)open the directory in which the above statement was passed		
  
3)create a views.py file as attached and edit the urls.py file as attached, make sure views.py is one folder outside the directory of urls.py
  
4)run the server locally on the prompt

`-->python manage.py runserver`   (make sure the current directory is the directory which hold manage.py)

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resources/4.PNG)
  
5)Type http://127.0.0.1:8000 in your web browser, your content would show up.

![alt text](https://github.com/Ayush19-01/GCI-Django-Hello-World/blob/master/resources/5.PNG)
