# yasm 

Dockerized Twitter-like platform developed as a part of Harvard's CS50w course.

## Requirements

Make sure [Docker](https://docs.docker.com/get-docker/) is installed, and the Docker Daemon is running on your machine prior to hosting the app.


## Hosting

### Clone the repository

```bash
git clone https://github.com/rQxwX3/yasm
cd yasm
```

### Build & run the Docker container

```bash
docker build -t yasm .
docker run -p 8000:8000 yasm
```

yasm should be available at http://localhost:8000 in your web browser.
