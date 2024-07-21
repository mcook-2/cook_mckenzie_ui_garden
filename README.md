## RunningInDocker

# Setting up and Running Your React UI Component Library in Docker

This Docker setup will allow you to host your React UI Component Library on localhost:8083.

## Prerequisites

- Docker installed on your machine

## Instructions

### Build Docker Image

1. Clone the repository or navigate to your project directory:
```
git clone https://github.com/mcook-2/cook_mckenzie_ui_garden
```
  Change to Directory of Repo:
```
cd cook_mckenzie_ui_garden
```

2. Build the Docker image:

```
docker build -t cook_mckenzie_assignment12 .
```

### Run Docker Container

3. Run the Docker container:

```
docker run -p 8083:8083 --name cook_mckenzie_assignment12 cook_mckenzie_assignment12
```

### Access the Application

4. Open your web browser and go to [http://localhost:8083](http://localhost:8083) to view your React UI Component Library.


### Run tests

5. Open docker container (cook_mckenzie_assignment12). Naviagte to "Exec". Run this command:

```
npm run test
```

