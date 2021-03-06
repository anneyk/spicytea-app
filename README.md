# spicytea-app

>[Annet Khavere](https://github.com/anneyk)  
  
# Description  
This is a neighborhood app where after signing up, a user is able to join a hood owned by the hood admin, and once you 
join a hood, one can see businesses and posts in that particular hood.
##  Live Link  
https://spiceytea-app.herokuapp.com/account/login/?next=/

## User Story  
  
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  
## Setup and Installation    
##### Cloning the repository:  
 ```bash 
https://github.com/anneyk/Spiceytea-app.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd spicytea-app/
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual 
- source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations
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
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
 
## Technology used  
  
* Python3
* Django
* Heroku

## License 
* Copyright (c) 2022 **Annet Khavere**
