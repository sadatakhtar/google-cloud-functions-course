# Google Cloud Functions Course
## Starting a project
To start a new project in Google Cloud, go to the [Firebase Console](https://console.firebase.google.com) or create it from [Google Cloud Platform Console](https://console.cloud.google.com).
## Creating a virtual environment
First we have to install `python3-venv` with the following command
```commandline
sudo apt install python3-venv
```
Then we execute the following command
```commandline
python3 -m venv venv
```
To activate the virtual environment on linux os
```commandline
source venv/bin/activate
```
In case you run into issues with venv and cannot activate the virtual environment try:
```
sudo apt install python3.10-venv
```
In order to add new packages to our new virtual environment we create a file called `requirements.txt`
and execute the following command
```commandline
pip install -r requirements.txt
```
