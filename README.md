## Dockerize Shell: app cowsay 

exampel taken from: O'REILLY - using Docker


## purpose of the example

to show Dockerfile functionality (ENTRYPOINT)

## result: 

will show a cow and his say


## Procedure

Build the Docker image:
```
docker build . -t <your username>/cowsay
```

run the image:
```
-docker run <your username>/cowsay
```
or
```
-docker run <your username>/cowsay "Hello World!"
```
