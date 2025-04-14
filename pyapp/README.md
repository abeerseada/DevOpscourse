docker ps
docker build -t py_app .
docker run --name py_con -p 3000:3000 py_app
docker logs py_con3