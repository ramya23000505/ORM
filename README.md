# Ex02 Django ORM Web Application
NAME: Ramya R
REG.No:212223230169
## Date: 
## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).
## Entity Relationship Diagram
Include your ER diagram here

## DESIGN STEPS
### STEP 1:
Clone the problem from GitHub
### STEP 2:
Create a new app in Django project
### STEP 3:
Enter the code for admin.py and models.py
### STEP 4:
Execute Django admin and create details for 10 books
## PROGRAM
File: models.py
```
from django.db import models
from django.db import models
class Employee (models.Model):
    empid=models.IntegerField()
    empname=models.CharField(max_length=20) 
    dept=models.CharField(max_length=20)
    salary=models. FloatField()
    aadhaar=models.BigIntegerField(null=True)
```
File: admin.py
```
from django.contrib import admin
from .models import Employee
admin.site.register(Employee)
```
## OUTPUT
![Screenshot 2024-04-03 175715](https://github.com/ramya23000505/ORM/assets/149370791/5847ce7f-91a2-45cf-bba3-69331a1d3d2c)

Include the screenshot of your admin page.
## RESULT
Thus the program for creating a database using ORM hass been executed successfully
