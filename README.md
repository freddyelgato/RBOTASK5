# RBOTASK5 - "Hello World" Application in Ruby

This project is a simple "Hello World" web application created in Ruby and deployed in a Docker container. You can run it locally and access it in your browser.

## Requirements
- **Docker**: [Install Docker](https://www.docker.com/get-started) if you don’t have it yet.

## Installation Instructions

1. **Clone this repository**:
   ```bash
   git clone https://github.com/freddyelgato/RBOTASK5.git
2. **Run the application in Docker**:
   ```bash
   docker run -d -p 3000:3000 --name rbotask5 2424833f/rbotask5
 - **d**: Runs the container in detached mode.
 - **p8080**: Maps container port 3000 to your machine's port 3000.

3. **Access the application in your browser to see the "Hello World" message**:
   ```bash
   http://localhost:3000
   
## Useful Commands
- View containers: `docker ps`.
- Stop the container: `docker stop RBOTASK5`.
- Remove the container: `docker rm RBOTASK5`.

## Enlaces
- Docker Hub Image: [docker ps](https://hub.docker.com/r/2424833f/rbotask5).

