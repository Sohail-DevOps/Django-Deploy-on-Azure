Django Application Deployment on Azure
This guide will walk you through the steps of deploying a Django application on Azure using GitHub Actions.

Table of Contents
Installing additional packages for deployment
Creating a settings file for deployment
Configuring the app to use deployment settings
Adding a requirements.txt file with all required packages
Adding a config file and .gitignore
Connecting to Azure and deploying the app
Step-by-Step Guide
1. Installing Deployment Packages
To prepare your Django application for deployment, install the necessary packages:
pip install psycopg2 python-dotenv whitenoise
