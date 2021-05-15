# SocialWebsite
This is a social website to create a custom profile for users to login, logout, edit their password and reset password.
Also adding Javascript with Ajax using Jquery bookmarklet to share content from other sites on the website.
And a follow system, create an activity stream.
Used Django signals to make data redundant in such a way that is optimizes read performance, dango signals come with dispatcher that allow
receiver functions get notified when action occur and integrate Redis allows you to save different types of data, 
It also has fast I/O operations storage to store items.

Tools:
social_django => "pip install social-auth-app-django"
descprition: social authenticatication to use service such as Facebook, Google, Twitter to let users use their accounts from other services.

django_extensions =>1- "pip install django-extensions"
others tools with django_extensions, 2- "pip install werkzeug" -> debugger layer 
3- "pip install pyOpenSSL" -> SSL/TLS functionality
4- To run => python manage.py runserver_plus --cert-file cert.crt
description: for running the developement server through https, but django developmenet server is not able to serve the site through https, 
so to work with https, we are going to use the RunServerPlus extension, it's third party collection of custom extensions for django.

thumbnail => "pip install easy-thumbnails"
description: to display optimized images

redis => firs, install Redis from the website => "https://redis.io/download", Then install => "pip install redis"
