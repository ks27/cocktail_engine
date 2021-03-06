# Cocktail Engine
[![Build Status](https://travis-ci.org/scwall/cocktail_engine.svg?branch=master)](https://travis-ci.org/scwall/cocktail_engine)
[![codecov](https://codecov.io/gh/scwall/cocktail_engine/branch/master/graph/badge.svg)](https://codecov.io/gh/scwall/cocktail_engine)


Software for the machine cocktail engine 


## :warning: Project for only raspberry pi :warning:

## Getting Started


The django project is used for manage and create cocktail from the cocktail machine, 
for more how to create the cocktail machine and configure raspberry pi. Please you refer to the [wiki](https://github.com/scwall/cocktail_engine/wiki/)

### Prerequisites

- [python 3.5 or more](https://www.python.org)
- [rabbitmq](https://www.rabbitmq.com/download.html)
- [chromium browser](https://chromium.woolyss.com/)
- [chromium driver](http://chromedriver.chromium.org/)


### Installing

```
Install python 3.5
Install pipenv : $ sudo pip3 install pipenv
Create env and install requirements: /cocktail_engine $ pipenv install --ignore-pipfile
Launch command: $ python manage.py runserver
                $ python manage.py loaddata engine/solenoidvalve.json
```

## How to use "Cocktail engine"
### At the launch of the application:

Launch server web, after install all packet. 
the server will be in debug mode if the production variable is not specified

### In the food selection function you will have to:

- Connect website

 If always in debug mode, you can reach the website by the address : 

[http://127.0.0.1:8000/](http://127.0.0.1:8000/)
 


## What is in django project
### You will find the following functions on the django project: 
you will have possibility of : create the cocktail by selecting the differents bottles, add or remove cocktail image, 
add or remove bottles in the solenoid valves and add or remove bottle image, 
put the bottles as empty for cannot create cocktail.

## Built With

* [python 3.5](https://www.python.org/) - The programming language 



## Authors

* **Pascal de Sélys** - *Initial work* - [scwall](https://github.com/scwall)

## Acknowledgments

I would like to thank my teacher for his advice,my classmates , openclassrooms for the courses amazing :D , my wife and my friends for her patient, and condolence to the cactus, cactus is dead :(
