
# Nginx Static File Server with Docker

A simple and easy-to-setup Docker-based solution to serve static files using Nginx. This project allows you to quickly deploy an Nginx container that serves content from a local directory, perfect for hosting static websites or assets with minimal configuration.

## Features

- Dockerized Nginx server for serving static files
- Simple configuration with Docker Compose
- Easy to deploy and use for static content hosting

## Prerequisites

- Docker
- Docker Compose

## Getting Started

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/nginx-folder-server.git
cd nginx-folder-server
```

### 2. Add Your Files

Place your static files (e.g., HTML, CSS, images) inside the `my-folder` directory.

### 3. Customize Nginx Configuration (Optional)

You can modify the `nginx.conf` file if you need to customize the Nginx server settings. By default, it serves files from the `/usr/share/nginx/html` directory.

### 4. Build and Run the Docker Container

Run the following command to start the Nginx container with Docker Compose:

```bash
docker-compose up -d
```

This will build and start the container, making your static content available at [http://localhost:8080](http://localhost:8080).

### 5. Access Your Site

Open your web browser and go to [http://localhost:8080](http://localhost:8080) to view the static files being served.

## Stopping the Server

To stop the Nginx server, run:

```bash
docker-compose down
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
