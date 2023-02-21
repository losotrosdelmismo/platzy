## conectarse al contenedor usando una terminal

// levantamos mongo en docker
docker-compose up -d mongodb


//entramos desde docker a la terminal
´´´sh
docker-compose exec mongodb bash
´´´

## conectarse con mongosh "" name conection

´´´sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false" //// (dir local)
´´´

## comandos simples
´´´sh
show dbs
show collections
´´´