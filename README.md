# Simple_Dockerfile

Creating a docker repository on Docker hub

### Build the image and name it 

---
docker build --tag php-mysqli-apache .
---

### Login tocker hub

---
docker login
---

### Tag the image

---
docker tag php-mysqli-apache{DOCKER_USERNAME}php-mysqli-apache:1.0
---

### push the image to your repository

---
docker push {DOCKER_USERNAME}/php-mysqli-apache:1.0
---

### Verify your vrepository exists
---
https://hub.docker.com/r/{DOCKER_USERNAME}php-mysqli-apache
---

