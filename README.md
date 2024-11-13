# SOCIAL MEDIA APP

This is a simple social media application developed using Flask and Python. The app allows users to register, log in, create posts, send messages, comments, like, unlike and send and receive notifications.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Prerequisites

Ensure the following are installed on your machine:

- **Python 3.x**: The version of Python required for the app.
- **pip**: Python package installer for installing the dependencies.

Check if Python and pip are installed by running:


- python --version
- pip --version


## Installation
### 1. Create a Virtual Environment
python -m venv venv

### 2. Activate the Virtual Environment
#### On Windows:
venv\Scripts\activate
#### On Mac/Linux:
source venv/bin/activate

### 3. Install the Required Packages
pip install -r requirements.txt


## Usage
### Set environment variable
#### On windows:
set FLASK_APP=app.py
#### On Mac/Linux:
export FLASK_APP=app.py

### Run the application
python app_runner.py
