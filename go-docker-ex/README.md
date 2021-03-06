in order to build image:
$ docker build -t my-go-app .

in order to run :

$ docker run -p 8080:8081 -it my-go-app

-p 8080:8081 - This exposes our application which is running on port 8081 within our container on http://localhost:8080 on our local machine.
-it - This flag specifies that we want to run this image in interactive mode with a tty for this container process.
my-go-app - This is the name of the image that we want to run in a container.
