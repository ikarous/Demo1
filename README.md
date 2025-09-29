# Demo1-Helloworld

Demo1-Helloworld is a simple Python FastAPI demo project with one endpoint that returns a JSON dictionary containing a key `message` with the value "Hello World".

## Installation

Install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Running the Project

Start the FastAPI server with:

uvicorn main:app


The API will be available at `http://127.0.0.1:8000`.
The docs page will be available at `http://127.0.0.1:8000/docs`.

## Endpoint

- `GET /`  
  Returns a JSON response:  
{ "message": "Hello World" }



## Example Request

Use the following `curl` command from your terminal to test the endpoint:
```bash
curl -X 'GET' 'http://127.0.0.1:8000/' -H 'accept: application/json'
```

Response:
{"message":"Hello World"}