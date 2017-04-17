## Django Project
Boilerplate code forDjango projects

### To get started
* cd into a new directory and clone this repo `git clone https://github.com/zkhan93/django_project.git .`
* Create a new Django app, let's call it todoapp by `python manage.py createapp todoapp`
* Edit [settings.py](projects/settings.py) file to include todoapp in INSTALLED_APPS
* Edit urlpatterns in [urls.py](projects/urls.py) file to include todoapp's routing rules - do not use root url.
* Start command line or terminal in [static](static/) folder and type 'bower install' this will install required dependencies, to add any dependencies required by your app please use this command 'bower install \<package_name\> --save'. know about bower at http://bower.io

### Bonus

* Scroll to the end of [settings.py](projects/settings.py) and change the value of admin.site.site_header,admin.site.site_title,admin.site.index_title variable to change the titles of administration section

### Some Important points to keep in mind while creating Django app to include in this project

* do not use root url, use prefixed app name so that it does not interfear other apps functionality and is easy to insert into this project
* keep you templates inside your apps name folder for example templates/\<app_name\>/\<template_name\>
