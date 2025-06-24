# hello_captain
Basic Docker project 


# Creating a basic Dockerfile
This is a basic Dockerfile to print `Hello, Captain!` on the console


## Project Requirements
- [Docker](https://docs.docker.com/get-docker/) installed on your system
- [Git](https://git-scm.com/) CLI for cloning repository


## How to run the Project

1. ** Clone the GitHub Repository:**
```bash
git clone https://github.com/jaydev576/hello_captain.git
cd hello_captain
```

2. **Build the Docker Image and Run:**
```bash
docker build -t hello_captain .
docker run --rm hello_captain
# --rm flag to remove the container after it exits
```

3. **Expected Output:**
```
Console
```
```
Hello, Captain!
```
