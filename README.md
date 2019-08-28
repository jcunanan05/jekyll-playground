# Jekyll Playground

Exploring how jekyll works. Setup with docker also included.

## How to run

### Docker

- Build the docker compose first. run `docker-compose buld`
- Run the container with ports. `docker-compose run --rm --service-ports jekyll_dev`

To run on multiple terminal windows:

- run `docker exec -it YOUR_CONTAINER_ID /bin/bash`

To cleanup:

- run `docker-compose down`

### Jekyll

To create a new project:

- run `jekyll new my_project`
