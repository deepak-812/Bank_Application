# Project Overview

https://user-images.githubusercontent.com/104820894/171664007-25b260a4-ed5a-40d5-a257-f3de722479dd.mp4

# How to use

Firstly make sure You have installed python and Django installed in your python...

then open mysql

-> create database dbbank;

now go to settings in bank folder and set your mysql password section

open bank folder(which you extracted now)

type cmd in address bar (to open cmd in bak folder) and type -> python manage.py makemigrations

next cmd in -> python manage.py migrate

open mysql

-> use dbbank;

-> insert into bankapp_cust values(101 , 'bnkadmin' , 'Deepak' , 10000 , '2022-03-21' , 1)

now open cmd in your extrated_location/bank

or (open bank folder(which you extracted now)

type cmd in address bar (to open cmd in bak folder) and type)

two dir with one file manage.py

address bar type cmd on address bar to open cmd in present location(bank location)

type in cmd -> python manage.py runserver


Admin login id is '101' and password is 'bnkadmin'
