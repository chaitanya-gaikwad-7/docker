# Hello World 
## using Docker, nodejs

```
mkdir -p node_app
cd node_app/
npm init
touch index.js
touch Dockerfile
docker build -t mynodeapp .
docker run -it -d -p 4500:4500 mynodeapp
```