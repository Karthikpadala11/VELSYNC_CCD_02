# VELSYNC_CCD_02 – Dockerized Flask App

## Project Overview
This project is part of the VELSYNC Cloud Computing & DevOps Internship.  
It demonstrates a simple Flask application running inside a Docker container.

**Features:**
- Flask web app with a single endpoint `/`  
- Returns the message: `Hello, Velsync!`  
- Containerized using Docker  


## Directory Structure
VELSYNC_CCD_02/
│
├── app.py # Flask application
├── requirements.txt # Python dependencies
├── Dockerfile # Docker configuration
└── README.md # Project documentation

I have cloned the repository from GitHub to my local machine using the following command:
           git clone https://github.com/Karthikpadala11/VELSYNC_CCD_02

Docker was installed on the local machine following the official Docker installation steps.
The installation was verified by running docker --version.

After installation, the Docker service was checked using sudo systemctl status docker and confirmed to be active and running.

The Docker image was successfully built from the project’s Dockerfile using docker build VELSYNC_CCD_02  . and verified with docker images.

A container was created and started from the Docker image VELSYNC_CCD_02 , allowing the application to run in an isolated environment.

The Docker container id  55649f85dbce container was run from the image VELSYNC_CCD_02   with port 5000 mapped to the host, allowing access to the application via http://localhost:5000.


