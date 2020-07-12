npm init -y (criar package json)
npm install express
npm install nodemon

docker ps (lista os containers)

docker stop 'idcontainer' (para de executar)
docker rm 'idcontainer' (remove)

docker build -t felipelima/dockernode .
docker run -p 3000:3000 -d felipelima/dockernode

docker-compose up

// "start": "nodemon --legacy-watch index.js"
