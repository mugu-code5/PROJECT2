# FastAPI Application Setup Guide

## Step 1: Create a Virtual Environment

It is recommended to use a virtual environment to manage dependencies.

### Windows:
```sh
python -m venv venv
venv\Scripts\activate
```

### Linux & macOS:
```sh
python -m venv venv
source venv/bin/activate
```

## Step 2: Install Dependencies

Ensure you have all required dependencies installed by running:
```sh
pip install -r requirements.txt
```

If you don’t have a `requirements.txt` file, you can manually install FastAPI and Uvicorn:
```sh
pip install fastapi uvicorn
```


## Step 3: Running the Application

Use the following command to start your FastAPI application:
```sh
python -m app.main
```

If you are using Uvicorn, you can run:
```sh
uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload
```
If you want to use python, you can run:
```python
python -m app.main
```

## Additional Tips

- To freeze dependencies:
  ```sh
  pip freeze > requirements.txt
  ```
- To deactivate the virtual environment:
  ```sh
  deactivate
  ```

