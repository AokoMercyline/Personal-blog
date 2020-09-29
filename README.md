# PERSONAL BLOG

## Published At
* Date 28/09/2020

## Description

Blog is a personal blogging website where you can create and share your opinions and other users can read and comment on them. blog also has random quotes that inspire the users.

## Author
 * Aoko Mercyline

<!-- ## [Live link] () -->

## Features

As a user of the web application you will be able to:

* See all submitted blogs
* See random quotes
* Subscribe to the blog
* Create an account
* Log in
* Post a blog
* Comment on a blog
* See comments posted on each individual blog
* Edit your profile i.e will be able to add a short bio about yourself and a profile picture


## Specification
| Behaviour | Input | Output |
| :------------ |:---------------:| -----:|
| view block post| sign up for account | sign in  |
| view post     | add post  | submit  |
| all post | view more    | see comments and add post |
| add post | update | delete

## Known Bugs
* No current test for the application

## Prerequisites

* python3.6
* virtual environment
* pip

## How to access it
You can access it by cloning the [Repository](https://github.com/AokoMercyline/Personal-blog)
```
$ Open Terminal (Ctrl Alt T)
$ git clone link
$ cd directory-name(Blog)
$ code .
```

## Running the Application

* Install virtual environment using $ python3.8 -m venv --without-pip virtual

* Activate virtual environment using $ source virtual/bin/activate

* Download pip in our environment using $ curl https://bootstrap.pypa.io/get-pip.py | python

* Install all the dependencies from the requirements.txt file by running python3.8 pip install -r requirements.txt

* Create an .environment file in the root of the folder and add the following code:

  export MAIL_USERNAME=<your-email-address>
  export MAIL_PASSWORD=<your-email-password>
  export SECRET_KEY=<your-secret-key>
Edit the configuration instance in manage.py from development to production

* To run the application, in your terminal:

  $ chmod a+x start.sh
  $ ./start.sh

 ## Create DB
* Create a psql databases

* CREATE DATABASE blog;
* CREATE DATABASE blog_test;
* Create the tables and run the migrations:

* pip install flask-migrate
* python3 manage.py db init
* python3 manage.py db migrate -m "Initial Migration"
* python3 manage.py db upgrade


## Technologies Used
* Python3.8
* Flask
* HTML
* Bootstrap
This application is developed using Python3.8, Flask, HTML and Bootstrap

## Support and Team

Aoko Mercyline

[Follow me here](https://github.com/AokoMercyline)


## LICENSE AND COPYRIGHT

[Mit License](https://opensource.org/licenses/MIT)2020 &copy; AokoMercyline





