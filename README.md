# Sprint 2 – Docker Containerization

This sprint focused on containerizing my Django blog application using Docker and Docker Compose. I installed Docker on my system, created a Dockerfile to build the application environment, and used docker-compose.yml to run the container. After building the image and running the container with `docker compose up`, the blog successfully loaded at `http://localhost:8000` from inside the Docker environment. I also logged into the Django admin panel and created two blog posts to confirm that the application and database were working correctly. This sprint helped me understand how Docker makes development more consistent, portable, and easier to manage.

## Images

### 1. Docker Containers Running
This screenshot shows the output of the `docker ps` command, confirming that the Django web container is active and running.

### 2. Django Homepage (Running in Docker)
This screenshot shows the blog homepage at `http://localhost:8000` while running inside Docker, including the two posts created for this sprint.

### 3. Django Admin Dashboard
This screenshot shows the Django admin panel after logging in, which confirms that the application is connected to its database and functioning properly inside the container.

## Screenshots

1. Docker containers running:  
   ![Docker containers running](images/docker_containers_running_sprint2.png)

2. Django app homepage:  
   ![Django app homepage](images/django-blogposts_sprint2.png)

3. Database connection successful:  
   ![Database connection](images/database_connection_sprint2.png)

