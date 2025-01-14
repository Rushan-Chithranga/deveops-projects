# Hello Captain Docker Image

This project contains a simple Dockerfile to create a Docker image that prints **"Hello, Captain!"** to the console when run.

## Features

- Lightweight base image: **Alpine Linux** (`alpine:latest`)
- Simple and efficient: Prints a message and exits
- Includes metadata using Docker labels

## Requirements

- Docker installed on your system ([Download Docker](https://www.docker.com/products/docker-desktop))

## Usage

### 1. Clone the Repository

Clone or download this project to your local machine.

### 2. Build the Docker Image

Run the following command to build the Docker image:
```bash
docker build -t hello-captain .
