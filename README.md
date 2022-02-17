﻿# polynomialbackend
# CLIP IT- A full stack pastebin clone made using the MERN stack.

<p align="center">
  <img width="370" height="140" src="https://i.ibb.co/4tCDdCN/11.jpg">
</p>

This is a MERN Stack based website where users can dump/paste some content or code of any language and they receive a short link to share

## Introduction
I had seen various chat application projects and tutorials in github ,youtube ,and other online resources. But in most of them it was a room where people can enter and chat, and security feature was not that good. So I decided to develop a chat application in django where one-to-one chat or private chat is possible keeping in mind the security features.

I had faced some difficulties while developing this application. I will brief about them and how to install it in your local system and run it in development server. The link to youtube video for deployment to heroku is provided [here](https://www.youtube.com/watch?v=UkokhawLKDU&list=WL&index=39).

## Screenshots
<p float="left" align="center">
  <img src="https://i.ibb.co/4tCDdCN/11.jpg />
  <img src="https://i.ibb.co/Np5hS1b/12.jpg" width="200" /> 
</p>
<p float="left" align="center">
  <img src="https://i.ibb.co/ZmYVpxC/13.jpg" width="200" />
  <img src="https://i.ibb.co/7kMv77w/14.jpg" width="200" /> 
</p>
<p float="left" align="center">
  <img src="https://i.ibb.co/RBbXnZK/image.png" width="200" />
  <img src="https://i.ibb.co/5knDgNX/image.png" width="200" /> 
</p>


## Demo and link to deployed the application
<video width="400" controls>
    <source src="./pastopedia/static/video.mp4" type="video/mp4">
</video>



The Clip It application is deployed in firebase platform. This is the link to the deployed application <b>:</b>
 [https://dustbin4devs.herokuapp.com/](https://dustbin4devs.herokuapp.com/)


 
## Technologies and tools used
* [Django-python](https://www.djangoproject.com/)
* [Html](https://www.w3schools.com/html/)
* [CSS](https://www.w3schools.com/Css/)
* [JavaScript](https://www.w3schools.com/js/DEFAULT.asp)
* [Python](https://www.python.org/doc/)
* [Bootstrap](https://getbootstrap.com/)



## Setup
First clone this repository to your local machine using the following command in git bash<b>:</b>

$ git clone https://github.com/Barenyakumar/dustbin4devs

Now open git bash in the root directory of the repository and enter the following command to install the required dependencies<b>:</b>

$ pip install -r requirements.txt
 
Inside the pastopedia directory there is another directory named pastopedia which is the django project directory. We have to make a few changes to /settings.py file in this directory.



Now in /settings.py file find the below code<b>:</b>

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
}


So we are done✌. Just few more steps to get it running in local server.

## Running in the local server(Optional)
Open the git bash inside the privatechat directory present in the root directory of the repository.
Run the following commands in order one by one:

$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py runserver
```
Follow the link generated after last command and Hurrah!🎉 the app is running.

## Deploying the app to heroku(Optional)
Now although it's running good in local server but to deploy to heroku we have to make few more changes. Refer to [this](https://www.youtube.com/watch?v=UkokhawLKDU&list=WL&index=39) tutorial for detailed step by step deployment to heroku.
