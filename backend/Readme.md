# Getting Started

First clone the repository from Github and switch to the new directory:

   
    $ cd backend/config
    
Activate the virtualenv for your project.
    
Install project dependencies:

    $ pip install -r requirements.txt
    
    
Then  apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver


## API Reference

### Authentication related Endpoints

#### Register


   POST /register/

username,email,password  



#### Login

  POST login/  

email, password  


#### upload / retrieving posts 

  POST post/  
  email, title, body, category

  GET post/  
  returns profanity error if detected  
  
#### search

  POST learn/search  
 
  

all JSON transactions






