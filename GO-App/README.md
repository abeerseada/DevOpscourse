go mod init   
go mod download   
go build -o ./app  
./app     
---
go run   
---
docker build -t go_app .    
docker run --name go_container -p 8080:8080 go_app  
docker start go_container  
docker exec -it go_container /bin/sh  
docker stop go_container  
docker rm go_container  
docker rmi go_app  
