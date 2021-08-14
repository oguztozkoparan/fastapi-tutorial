# FastAPI Learning

## Create Virtual Environment

I prefer to create a virtual environment but that is up to you.

> python -m virtualenv fastapi_env

- ### Activate Virtual Environment

  - In PS:
    > ./fastapi_env/Scripts/activate
  - In Terminal:
    > source fastapi_env/bin/activate

- ### Deactivate Virtual Environment

  > $ deactivate

## Installing

Install it with all the optional dependencies and features using `[all]`.
Installs `uvicorn` too.

> pip install fastapi[all]

## Run Server

`uvicorn` server up with the name of our filename, app and reload on change!

> uvicorn [filename]:app --reload

_This is a basic setup as they teach on their site._
