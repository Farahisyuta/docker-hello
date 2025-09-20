# Docker Hello Name

This project demonstrates a simple Docker image that prints a personalized greeting to the console.

## Features

- Uses `alpine:latest` as the base image.
- Prints `Hello, [name]!` to the console.
- Allows you to pass your name as a **build argument** or **environment variable**.

---

## Usage

### 1. Default greeting
```bash
docker build -t hello-name .
docker run --rm hello-name
https://roadmap.sh/projects/basic-dockerfile
