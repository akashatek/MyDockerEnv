# Flask Docker App

Reference:
 * [How to Dockerize a Flask Application](https://www.freecodecamp.org/news/how-to-dockerize-a-flask-app/)

Docker Build
```
docker build --tag flask-docker-app:1.00 .
````

Docker Run
```
docker run -d --name flask-docker-app -p 5001:5000 flask-docker-app:1.00
```