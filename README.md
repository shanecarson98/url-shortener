# url-shortener
System to shorten URLs

## To run:
Fill out .env file as needed.  Look at .env_sample for guidance
Create python virtual environment: `python -m venv venv`
To start python virtual environment: `source venv/bin/activate`
run to install required dependencies: `python pip install -r requirements.txt`

To spin up server to run program: `uvicorn shortener_app.main:app --reload`
`Ctrl + v` to stop uvicorn server

To reach your app, navigate to your `BASE_URL` entry in .env

To end virtual environment: `deactivate`