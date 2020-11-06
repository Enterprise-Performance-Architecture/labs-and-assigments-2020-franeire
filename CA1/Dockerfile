FROM python:3
# The First line of the Dockerfile is the FROM instruction
# this specifies the valid image name to be used, we are using python3 from docker
WORKDIR /CA1
# This command is used to set the working directory to be used
COPY index.html /CA1
# Our CA has one file to be used, I have called mine index.html and this has to be copied
CMD python -m http.server 8080
# The CMD, is the command to be executed by the container, in our CA we have been asked to
# use a python3 HTTP server module listening on Port 8080
