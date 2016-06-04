# Django Project
A central django project and setting to host all my Django apps

to install add a app to this project you need to complete the following actions
* Edit the [settings.py](projects/settings.py) file to include the app in INSTALLED_APPS
* Edit urlpatterns in [urls.py](projects/urls.py) file to include your apps urls - do not use root url.
* Start command line or terminal in [static](static/) folder and type 'bower install' this will install required dependencies, to add any dependencies required by your app please use this command 'bower install \<package_name\> --save'. know about bower at http://bower.io
* Scroll to the end of [settings.py](projects/settings.py) and change the value of admin.site.site_header,admin.site.site_title,admin.site.index_title variable to change the titles of administration section

#### Some Important points to keep in mind while creating Django app to include in this project
* do not use root url, use prefixed app name so that it does not interfear other apps functionality and is easy to insert into this project
* keep you templates inside your apps name folder for example templates/\<app_name\>/\<template_name\>
