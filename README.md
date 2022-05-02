# anonymization-api

Only one route is defined that accepts POST requests on the path `/entities`. It's purpose is to anonymize provided text.

## How to run
Clone this repository to your local machine. Then execute following commands from the root of the repository (e.i. `anonymization-api` folder)
:

1. `cd services`
2. `docker-compose up --build`

Open your browser at http://127.0.0.1:8000/docs to see API documentation