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

### Referência
* [Docker para desenvolvedores - Rafael Gomes](https://leanpub.com/dockerparadesenvolvedores)