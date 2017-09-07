## Dockerize Shell: app cowsay 

example taken from: O'REILLY - using Docker


## Purpose of the example

to show Dockerfile functionality (ENTRYPOINT)

## Result: 

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
