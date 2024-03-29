# BLOG

## By **limooh brian**

## Description

This is an application that allows a writer to publish blog posts and users can view and comment on the blog posts.

## Technologies used

python

## Behaviour Driven Development(BDD)

| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| to add post | click on sign up |  fill in the registration field |
| to add post if u had already signed up | click on login | fill in the field |

## Known bugs

no bugs

## SetUp / Installation Requirements

### Prerequisites

* python3.6
* pip
* Virtual environment(virtualenv)

### Cloning

* In your terminal:

        ` $ git clone https://github.com/limobrian/IP-BLOG.git

        ` $ cd ip-blog

### Creating the virtual environment

        `$ python3.6 -m venv --without-pip virtual

        `$ source virtual/bin/env

        `$ curl https://bootstrap.pypa.io/get-pip.py | python

### Installing Flask and other Modules

        `$ python3.6 -m pip install Flask

        `$ python3.6 -m pip install Flask-Bootstrap

        `$ python3.6 -m pip install Flask-Script
        
         `$  pip install flask-wtf 
         
         `$  pip install flask-SQLAlchemy 
         
         `$ pip install psycopg2 
         
         `$ pip install flask-migrate 
         
         `$ pip install flask-login
         
         `$ pip install flask-uploads
         
         `$ pip install flask-mail
         
         `$ pip install flask-simplemde markdown2
         
         `$pip install gunicorn

## Setting up the API Key

To be able to gather article info from the News API you will need an API Key.
Visit     and register for an API key.
In the root directory of the project folder create a file: start.sh
Insert the following info into it:
export NEWS_API_KEY=''
python3.6 manage.py server
Insert the API Key you received from News Api where is.

## Running the Application

* To run the application, in your terminal:

        `$ chmod a+x start.sh
        `$ ./start.sh

## LICENSE

The application is under an [MIT License].

## Contact Information

You can contact me via my gmail account limobrian290@gmail.com