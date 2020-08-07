# Docker

### Install
* [Docker Engine](https://docs.docker.com/engine/install/)
* [Docker Compose](https://docs.docker.com/compose/install/)
* [Docker Machine](https://docs.docker.com/machine/install-machine/)

---

#### Run
~~~bash
docker build --pull --rm -f "Dockerfile" -t docker:latest "."
docker-compose -f "docker-compose.yml" up -d --build 
~~~

---
### Tutorial 
#### Creating the Dockerfile
~~~
touch Dockerfile \
echo "FROM python:3.8.5-alpine" > Dockerfile
# set image
docker build .

## docker compose
touch docker-compose.yml
~~~



---
### Referência
* [Docker Hub](https://hub.docker.com/_/python?tab=description) 
* [Docker para desenvolvedores - Rafael Gomes](https://leanpub.com/dockerparadesenvolvedores)
* [runnable.com](https://runnable.com/docker/python/docker-compose-with-flask-apps)
* [rollout.io](https://rollout.io/blog/using-docker-compose-for-python-development/)