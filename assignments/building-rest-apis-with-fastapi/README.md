# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to practice defining endpoints, handling path parameters, validating request data, and returning appropriate HTTP status codes.

## 📝 Tasks

### 🛠️ Set Up the FastAPI Application

#### Description
Create and run a minimal FastAPI application so you can explore its interactive API documentation.

#### Requirements
Completed program should:

- Install FastAPI with its standard dependencies.
- Create a `main.py` file with a FastAPI application instance.
- Add a `GET /` endpoint that returns a JSON welcome message.
- Run the app with `fastapi dev main.py` and verify the endpoint in `/docs`.


### 🛠️ Add Task-Reading Endpoints

#### Description
Represent tasks as in-memory records and create endpoints for listing tasks and retrieving one task by its ID.

#### Requirements
Completed program should:

- Store task records with an `id`, `title`, and `completed` value.
- Implement `GET /tasks` to return the task list as JSON.
- Implement `GET /tasks/{task_id}` to return the matching task.
- Return an HTTP 404 response when the requested task ID does not exist.


### 🛠️ Create Tasks with Request Validation

#### Description
Add an endpoint that accepts a JSON request body, validates its data, and creates a task.

#### Requirements
Completed program should:

- Define a Pydantic request model that requires a non-empty task title.
- Implement `POST /tasks` to accept a valid request and create a task with a unique ID and `completed` set to `false`.
- Return the created task with an HTTP 201 status code.
- Use `/docs` to submit a valid request and verify the response.
