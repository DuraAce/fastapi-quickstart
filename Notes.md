## to create and use venv in linux
1. Go to project dir
- `cd current_dir`
2. Create a virtual env named "env"
- `python3 -m venv env`
3. To activate
- `source env/bin/activate`
4. To deactivate
- `deactivate`


## Save and install dependencies
1. To save current packages
- `pip freeze > requirements.txt`
2. To install the same packages
- `pip install -r requirements.txt`

## Run FastAPI application using Uvicorn
`uvicorn main:app --reload`

## Run FastAPI application using Uvicorn with specific listening host and port
`uvicorn main:app --host 0.0.0.0 --port 8080 --reload`

## To see the docs, go to below page:
host:port/docs
host:port/redoc
host:port/openapi.json