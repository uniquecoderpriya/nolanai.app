# **[Nolanai.app](https://www.nolanai.app/)** clone with **[ChatGPT](https://chat.openai.com/)** 

## Project Preview
[![Project Demo](http://img.youtube.com/vi/cR3qgOs66xw/0.jpg)](http://www.youtube.com/watch?v=cR3qgOs66xw)

# Quick Start

## Download Python 3.10.11
<a href="https://www.python.org/ftp/python/3.10.11/python-3.10.11-embed-amd64.zip" target="_blank" >Download</a>

## Download git
<a href="https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-64-bit.exe" target="_blank" >Download</a>

## Git Clone 
``` git clone https://github.com/EshaanManchanda/Nolanai.app_Clone.git . ```
## Download and make Virtualenv 

``` pip install virtualenv ```
``` virtualenv venv```
``` venv/Scripts/activate```
## Download all Requirements

``` pip install -r requirements.txt ```
## Creat an .env file 
Generate you <a href="https://platform.openai.com/api-keys" target="_blank" >API KEY </a>
```CHATGPT_KEY= add_your_api_key ```

## Make database

``` python manage.py migrate ```

## Runserver

``` python manage.py runserver ```

## Home page
<img src="./assets/output/home.jpg" alt="Home page of Nolanaiapp" width="50%"/>
## Create Script page
<img src="./assets/output/createscriptpage.jpg" alt="create script page of Nolanaiapp" width="50%"/>
## script page
<img src="./assets/output/script.jpg" alt="script page of Nolanaiapp" width="50%"/>
