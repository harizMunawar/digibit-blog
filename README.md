
![GitHub contributors](https://img.shields.io/github/contributors/digibitstudio/digibit-blog)
![GitHub forks](https://img.shields.io/github/forks/digibitstudio/digibit-blog?style=social)
![GitHub stars](https://img.shields.io/github/stars/digibitstudio/digibit-blog?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/digibitstudio/digibit-blog)
![GitHub issues](https://img.shields.io/github/issues/digibitstudio/digibit-blog)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

<p align="center">
  <h3 align="center">Digibit Blog</h3>

  <p align="center">
    Digibit Studio Official Blog Site
    <br />
    <a href="https://github.com/digibitstudio/digibit-blog"><strong>Explore the docs »</strong></a>
    <br />
    <br />    
    <a href="https://github.com/digibitstudio/digibit-blog/issues">Report Bug</a>
    ·
    <a href="https://github.com/digibitstudio/digibit-blog/issues">Request Feature</a>
  </p>
</p><br>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Admin Site](#admin-site)
  * [Google API](#connecting-with-the-google-api)
* [Our Team](#our-team)
* [Contributing](#contributing)

<!-- ABOUT THE PROJECT -->
## About The Project

A Django app that handle the flow of a report card management for school. This app will produce a dynamic pdf file that can be downloaded. This app is a submission for my "Project Work" assignment

### Built With

* [Python](https://www.python.org/)
* [Django](https://www.djangoproject.com/)
* [Visual Studio Code](https://code.visualstudio.com/)
* Love

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

These are list of things you need to have before you use the project and how to install them.
* Python<br>
Download the Python installer [here](https://www.python.org/downloads/) (preferably Python 3.8)<br>
Run the installer
* Text Editor<br>
You can choose any text editor that suits you the most, but I reccomend using Visual Studio Code<br>
Download the VSCode installer [here](https://code.visualstudio.com/download)<br>
Run the installer

### Installation
To get started, Install the requirements.txt<br>
You can use any virtual environment you want, but I prefer [virtualenv](https://pypi.org/project/virtualenv/)

__1. Setting Up Virtual Environment__<br>
Open terminal in the root directory of this project
```
pip install virtualenv env
```

__2. Activate Your Virtual Environment__<br>
For Windows
```
cd env/Scripts
activate.bat
```
For Linux
```
cd env/bin
activate
```

__3. Install The requirements.txt__<br>
In the root directory of this project
```
pip install -r requirements.txt
```

__4. Migrating The Models__<br>
In the root directory of this project
```
manage.py migrate
```

__5. Create SuperUser Account__<br>
In the root directory of this project
```
manage.py createsuperuser
```
You can input any data for the superuser account<br>
But please remember them, as it is used to login to the admin site

__6. Running The Server__<br>
In the root directory of this project
```
manage.py runserver
```
Default port is 8000, so access the [server](127.0.0.1:8000) there

### Admin Site
To access the admin site visit the /admin url<br>
You will need your "Nomor Induk" & "Password" from [step 5](#installation) as a login authentication

### Connecting With The Google API
To connect with the Google API, please login to the [admin site](#admin-site)

Find the Sites, then click "ADD SITES"
* Put "http://127.0.0.1:8000" as domain name
* Put "Digibit Blog" as display name

Find the Social Applications, then click "ADD SOCIAL APPLICATION"<br
* Select "Google" as provider
* Put "Digibit Blog" as name
* Put "233648956225-dvstkstqpvvuhmuir69nipprs7df71pn.apps.googleusercontent.com" as client id
* Put "N-lqVfx7VZHl9TtuK7815ODU" as secret key
* Leave the key field empty
* And then choose site


## Our Team
* **Back-end team**: [Hariz Sufyan Munawar](https://github.com/harizMunawar)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

