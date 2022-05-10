# Country Capital API
<hr>
This is the project were it will returns the name of the country when the capital city is provided.

## Prerequisites
* Install the virtual environment package<br>
```html
$ pip install virtualenv
```
* Create a virtual environment<br> 
```html
$ virtualenv <Virtual Environment name>
```
* Activate your virtual environment with the command<br>
```html
$ <Virtual Environment name>\Scripts\activate
```
* With the virtual environment properly activated, install the plugins available at the **requirements.txt** file through the command<br>
```html
$ pip install -r requirements.txt
```
* Config for flask<br>
```html
$ export FLASK_APP=app.py
```
<br>

```
html
$ export FLASk_ENV=development
```

## Deployment
```html
$ flask run
```
<br>

```html
$ uvicorn main.py
```
## API endpoints 
* Microservice endpoint for API is available in this url<br>
```html
[Description](https://example.com/country-capital/<query-params>)
```