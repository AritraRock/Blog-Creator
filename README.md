# Blog Creator backend

## Overview
This project is a backend API built using [FastAPI](https://fastapi.tiangolo.com/) where a user can create an authenicated account and post, show his/her blogs. API endpoints can be checked here https://fastapi-blog-creator.vercel.app/docs
## Features
- User authentication: Secure and simple authentication mechanism for users.
- Automatic interactive API documentation with Swagger UI and ReDoc.
- Built-in validation based on Pydantic.

## Installation

### Prerequisites
- Python 3.7+
- pip (Python package installer)

### Steps
1. Clone the repository:
    ```sh
    git clone https://github.com/AritraRock/Blog-Creator.git
    cd Blog-Creator
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Running the Application
To start the FastAPI server, run:
```sh
uvicorn app.main:app --reload
```
## Deployment

The application has been deployed on Vercel and is accessible at https://fastapi-blog-creator.vercel.app/.

To check the API endpoints and interactive documentation, visit:

https://fastapi-blog-creator.vercel.app/docs

