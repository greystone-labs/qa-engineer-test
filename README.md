# QA Engineer Challenge

## Setup

Prereqs:
```
 * python 3.7+
 * (optional) conda or virtualenv
```

Install Dependencies:
```
 $ cd <repo>

 # create/switch into virtual environment if using (recommended)
 $ pip install -r requirements.txt
```

## Run Server:  
```
 $ python main.py

 # navigate to localhost:8000 in browser
```

## Notes
* Loading the index at `localhost:8000` will redirect to `localhost:8000/docs`, where you can view the OpenAPI spec and use the interface to test calls to the API. 
  * The OpenAPI Spec can also be imported into a tool like Postman for API testing.  
