# For a flask application of the soachart with a timerangeselector
## How to set up
Start by cloning my repo.

``` bash
$ git clone https://github.com/ballardinimarta/flasksoagraph.git
```
Go to the repos directory

``` bash
$ cd flasksoagraph
```

Install requirements.txt

``` bash
$ pip install -r requirements.txt
```

## How to host the Flask application on your localhost

When you are in the working directory and have activated the venv go to terminal and set

``` bash
$ export FLASK_APP=flaskapp/app.py
```
## How to run

and then you just do a flask run to connect to the server
``` bash
$ flask run
```
## Output
The output from the flask run command should be
``` bash
$ flask run
* Serving Flask app "flaskapp/app.py"
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
__Then the application should be visible at http://127.0.0.1:5000/ .__

#### Goodluck! :+1:
