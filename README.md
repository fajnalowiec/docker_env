# Base Docker LAMP Env

In total 3 containers are installed:

* php + apache (localhost:8080)
* mysql
* phpMyAdmin (localhost:8081)

## Important

1. In file **docker_compose.yml** adjust section **volumes** for image **dev-www-image** for your local paths.
2. In file **Dockerfile.dev-www-image** adjust the command **RUN git config** and provide your name/email needed while using git daily.
