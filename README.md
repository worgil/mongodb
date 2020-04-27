# mongodb
This is mongodb with ubuntu. You need just;
docker build -t mymongo:latest .
docker run -d --name mongo -p 27017:27017     -e MONGO_INITDB_ROOT_USERNAME=admin     -e MONGO_INITDB_ROOT_PASSWORD=password mymongo:latest --replSet rs0
you can use all mongod flags.

