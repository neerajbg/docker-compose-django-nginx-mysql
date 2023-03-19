# Deploy Django, Nginx and MySql with Docker Compose

This repository contains code to deploy Django, Nginx and MySql containers with Docker Compose.

Nginx will serve web requests on port 80. For serving Django application running on port 8001, we are using Gunicorn.

# Usage

After cloning the repository Run

```
Build the image : docker compose build

Run the containers : docker compose up

Close the containers : docker compose down
```
