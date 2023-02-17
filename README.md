# CS50 Project 

# Learn Basics of FAST API
    #### Video Demo:  [VideoScribe Video](https://www.youtube.com/watch?v=RO6OVLj2JWo)
    #### Description: Learn FastAPI basics providing simple example of GET, POST, PUT and DELETE Operations

## Pre-Requsites/Dependencies
Python 3.7+ versions are compatible

## Requirements
    * fastapi - framework to create Python APIs
    * uvicorn - Server to host the APIs
    * httpx - Test the app using TestClient

Requirements can be installed using the below command. Under the root directory of the project
```console
$ pip install requirements.txt
---> 100%
```

## PY file explanations
    * project.py - Main File of the project with all the methods
    * test_project.py - Test cases with appropriate +ve and -ve scenarios  


## Execution
    * project.py has the crud operations
  
To run the main and start the uvicorn server to have the fast api hosted below is the command.
The command calls the main method to run "uvicorn.run(app, host="0.0.0.0", port=8000)"

```console
$ cd project 
project/ $ python project.py
INFO:     Started server process [5119]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     Uvicorn running on http://0.0.0.0:8000 (Press CTRL+C to quit)
```

## Test Execution
    * test_project.py has test functions
  
To run the main and start the uvicorn server to have the fast api hosted below is the command  
```console
$ cd project
project/ $ pytest test_project.py
=================================================================== test session starts ====================================================================
platform linux -- Python 3.11.1, pytest-7.2.0, pluggy-1.0.0
rootdir: /workspaces/19798980/project
plugins: anyio-3.6.2
collected 10 items                                                                                                                                         

test_project.py ..........                                                                                                                           [100%]

==================================================================== 10 passed in 0.37s ====================================================================
project/ $ 
```

### Interactive API docs

Now go to <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

You will see the automatic interactive API documentation (provided by <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger UI</a>):

![Swagger UI](https://github.com/girisheduru/CS50GKE/blob/main/Screenshot%202023-02-17%20at%2000.41.41.png)

### References & Tutorials
 - https://fastapi.tiangolo.com/
 - https://www.youtube.com/watch?v=tLKKmouUams

