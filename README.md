
# Django Application Setup Guide

# Project Overview

A Django application is built using the Django web framework to create dynamic, scalable, and maintainable web applications. Here's an overview of the core components and structure involved in a typical Django project

# prerequisites

Before you begin, ensure you have the following installed on your Linux system:

* Update your package list and install curl and git

```bash
sudo apt update
sudo apt install curl git -y
```

## How to Set Up and Run the Django Application

* Clone the repository

```bash
https://github.com/rsingh0706/Django-Application.git
```
## Linux Essentials

Update your package list and install need Python and pip

1.install pythan 3.10 on your system, follow these steps depending on your operating system.

* Update the package list

```bash
sudo apt update
```
* Install required dependencies

```bash
sudo apt install software-properties-common
```
* Add the deadsnakes PPA repository

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
```
* Install Python 3.10

```bash
sudo apt install python3.10
```
* Verify the installation

```bash
python3.10 --version  (Python 3.10.15)
```

2. install pip (the package manager for Python) on Ubuntu, follow these steps

* Update the package list

```bash
sudo apt update
```
* Install pip for Python 3

```bash
sudo apt install python3-pip
```
* Verify the installation

```bash
pip3 --version  (pip 20.0.2 from /usr/lib/python3/dist-packages/pip (python 3.8) )
```

### Install Virtualenv (Optional but Recommended) 

It's a good idea to create a virtual environment for your Django project to manage dependencies independently.

* Install virtualenv:

```bash
sudo pip3 install virtualenv
```
* Create a virtual environment for your project:

```bash
virtualenv django_env
```
* Activate the virtual environment:

```bash
source django_env/bin/activate
```

### Install Django

You can now install Django inside your virtual environment (or globally if you skipped the virtual environment setup):

```bash
pip install django
```
* Verify the installation:

```bash
django-admin --version
```
* Configure Database and Migrate

```bash
python3 manage.py migrate
```
* Run Django Development Server

```bash
python3 manage.py runserver
```
* Start the application

```bash
python3 manage.py runserver 0.0.0.0:8000
```
By default, the app will be available at http://localhost:8000





