# Minimal Flask App in Docker

Copy directory and files, then follow cmds:

1.) 'sudo docker build -t flask:latest .'
2.) 'sudo docker run --name flask -p 5000:5000 flask:latest'


Sources:

This project contains a minimal Flask application based on the official  
[Flask Quickstart](https://flask.palletsprojects.com/en/stable/quickstart/) guide.  
The app is packaged in a Docker container.

As well info from the official
[Docker Hub](https://hub.docker.com/_/python) website.
This gave the Dockerfile template.
