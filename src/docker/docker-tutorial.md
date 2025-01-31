# Docker Tutorial

hello-docker

hello-docker/app.js
```js
console.log("hello docker!");
```

hello-docker/Dockerfile
```
FROM node:alpine
COPY . /app
WORKDIR /app
CMD node app.js
```

```bash
docker build -t hello-docker .
```