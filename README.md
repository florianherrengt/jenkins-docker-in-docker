### Getting started ###

Build the image

    docker build -t tagname .

Run it

    docker run --privileged -t -i -p 8080:8080 tagname

Jenkins is running on port 8080

Test docker in docker:

    docker ps
    docker exec <container_id> docker ps

### Credit ###

Docker in Docker: https://github.com/jpetazzo/dind

Jenkins: https://registry.hub.docker.com/_/jenkins/
