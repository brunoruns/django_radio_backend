# django_radio_backend
Experimenting with a Python Django backend framework for the radio project

First commit on the readme file

## conda environment
You can create a conda environment with 
- conda env create -n django_radio --file environment.yml
- conda activate django_radio 

## Getting started with Django
https://docs.djangoproject.com/en/4.2/intro/overview/
Taking a cue from https://docs.djangoproject.com/en/4.2/intro/tutorial01/

## setting up
The name chosen for the project is 'radiobackend'; Run the following command:
django-admin startproject radiobackend

## running the project
python3 manage.py runserver

## creating the first app in the project
The name chosen for the app is 'polls'
python3 manage.py startapp polls