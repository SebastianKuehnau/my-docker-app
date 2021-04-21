# my-docker-app
this is a simple example how to run a vaadin app in a docker container.

1. Build the Vaadin Application via `mvn install -Pproduction`

2. Create the Docker Image with `docker build -t vaadin-docker .`

3. Run the Docker Container with `docker run -ti -p 8090:8080 vaadin-docker`
