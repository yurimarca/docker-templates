# Hello World with HTML

This Docker template runs a simple web server using NGINX to display a "Hello World" HTML page.

## Files
- `Dockerfile`: Defines the container.
- `index.html`: Contains the "Hello World" HTML page.
- `command.sh`: build and run docker

## How to Build and Run

   ```bash
   docker build -t hello-world .
   docker run -d -p 8080:80 hello-world
   ```
