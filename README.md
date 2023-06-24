## Dockerized Simple Node.js Application

This repository contains a Dockerized version of a simple Node.js application. Docker allows you to package the application and its dependencies into a container, providing an isolated and consistent environment for running the application.

### Prerequisites

To use this Dockerized application, you need to have Docker installed on your machine. You can download and install Docker from the official website: [https://www.docker.com/](https://www.docker.com/).

### Getting Started

To get started with this application, follow the steps below:

1. Clone this repository to your local machine using the following command:

2. Change into the cloned directory:


3. Build the Docker image by running the following command:
      docker build -t your-image-name .

4. Once the image is built, you can run the application in a Docker container using the following command:
      docker run -p 3000:3000 your-image-name

5. Open your web browser and navigate to `http://localhost:3000` to access the running application.

