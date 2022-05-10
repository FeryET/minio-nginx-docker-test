# Minio behind NGINX using Docker Compose

This projects aims to make Minio console accessible behind an nginx. There are two files, one is `docker-compose.ssl.yml` which uses `nginx-certbot` docker image for creating SSL certifications, and making the connection secure, the other is `docker-compose.insecure.yml`, which uses the plain `nginx` docker image availabe in docker hub.
