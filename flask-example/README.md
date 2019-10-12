# Exercise 2 - Flask Example

## Build the image as:
`docker build -t test .`

## Run the container as:
`docker run  -p 80:8080 test`

## Test the site using curl from another terminal window:
`curl http://0.0.0.0/`

## Remove the container
`docker ps`
`docker stop CONTAINER_ID`

