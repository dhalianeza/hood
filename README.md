# HomeWatch

[dalianyiraneza] 
  
# Description  
Tis is a neighborhood app where a user must signup first, be able to join a hood owned by the hood admin, and once you 
join a hood, one can see businesses and posts in only that wood they belong to.  
##  Live Link  
 Click [View Site](https://dahood.herokuapp.com/) 
  
 
## User Story  
  
* Sign in/create account  to acccess the application .
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  
## Setup and Installation  
To get the project .......  
 
##### Install and activate Virtual  
 
- python3.6.12 -m venv virtual - source virtual/bin/activate  

##### Install Dependencies  
 
 pip install -r requirements.txt 
  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations hood
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python3.6 manage.py runserver 
```
Open the application on your browser `127.0.0.1:8000`.  
  
 
## Technology used  
  
* [Python3.6.12](https://www.python.org/)  
* [Django 2.2.6](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs  everythings works well
## Contact Information   
In case you have any question or suggestions, please email me at [daliaprecious4@gmail.com]
## License 
   
* Copyright (c) 2021 **preciousdarly**