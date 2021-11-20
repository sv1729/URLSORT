# This is a basic URL shortener 

- This is built using python web framework `flask` and `sqlite` database.

## Steps to run locally

1. clone the repository `git clone https://github.com/krishnagopal596/urlslicer.git`
2. create a virtual environment using `python -m venv venv` or `virtualenv venv`
3. Now activate the virtualenv using `\venv\Scripts\activate` or `source venv/bin/activate`
4. Now install packages using `pip install -r requirements.txt`

5. Initialize the database using 
    `python init_db.py`
6. Now run to the application create a `.env` file in the same folder as `app.py`
7. paste below contents in `.env` file
    ```env
    FLASK_APP=app
    FLASK_ENV=development
    ```
8. If ypu are running the app in production change `FLASK_ENV` to ` production`

9. now run the app using `flask run` 

Note: all commmands after step3 must be executed while virtualenv is activated.

#### Open http://localhost:5000 to go to the app


ypu enter the lomg url in the input and press submit and shirt url appears down press copy url button to copy it and  paste it in another browser window.

