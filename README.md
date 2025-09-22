# Ex02 Django ORM Web Application
# Date:21:09:2025
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM
## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
```
from django.db import models
from django.contrib import admin
class car_Inventory(models.Model):
    plate_No=models.charField(max_length=20,primary_key=True)
    car_Model=models.charField(max_length=100)
    car_Type=models.charField(max_length=20)
    Mileage=models.IntegerField()
    Make_Date =models.DateField()
    car_pic=models.ImageField()
class car_InventoryAdmin(admin.ModelAdmin):
    list_display=(' plate_No','car_Model','car_Type',' Mileage','Make_Date',' car_pic')

```
# OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-09-22 133940" src="https://github.com/user-attachments/assets/4ffe8abd-2e46-4cd4-be97-6b3614fdee13" />


# RESULT
Thus the program for creating a database using ORM hass been executed successfully
