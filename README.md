# File Upload API Demo

Demo project of a simple File Upload API using FastAPI and Python.

## Features
- Upload files via POST /upload
- Retrieve files via GET /files/{filename}

## Tech Stack
- Python 3.11
- FastAPI
- Uvicorn

## Run locally
```bash
python3 -m pip install -r requirements.txt
uvicorn main:app --reload --port 8000