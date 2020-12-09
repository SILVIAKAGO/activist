# Django-Chart

A web application whereby a user is able to vote multiple times on a particular subject


### Here is a sneak peek ...

![](images/image1.png)


## Getting Started

To get a copy of the project up and running on your local machine for development and testing purposes, 
1. Set up a Python development environment that includes; Python, **pip** & **a virtual environment** 
   ```bash
   $ python3 -m venv virtual

   $ source virtual/bin/activate

   ```
```

### Prerequisites

1. Install project *****dependencies*****
   ```
    (virtual) $ pip install -r requirements.txt
    ```
* See deployment for notes on how to deploy the project on a live system.


### Installing

1.  To get a development env running, use the **.env.example** file to create your own **.env** file.
2.  Create a **postgres** db and add the credentials to .env file
```
(virtual)$ psql
pc-name=#  CREATE DATABASE <name>;
```
3.  Apply initial migrations
```sh 
(virtual) $ python manage.py migrate 
```
4. Make migrations to your database
```sh
(virtual) $ python manage.py makemigrations application
(virtual) $ python manage.py migrate
```
5. Create admin account
```
(virtual) $ python manage.py createsuperuser
```
6.  Start development server
```
 (virtual) $ python3 manage.py runserver
 ```


#### Run the app
```bash
python3.6 manage.py runserver
```

# CREDITS
##### Google.com ⭐️ StackOverflow.com ⭐️

# Support and Contacts
In case You have any issues using this code do not hesitate to get in touch with me through deejaykayslyk@gmail.com or leave a comment here on Github.

## Known Bugs
None so far.
