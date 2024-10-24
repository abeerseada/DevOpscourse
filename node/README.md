# Node.JS Application
install node:
```
brew install node
```

install express:
```
npm install express
```

generate a package.json:
```
npm init -y
```

build docker image 
```
docker build -t node-img .
```
Run the Docker Container:
```
docker run -it --name node-container -p 8080:8080 node-img
```
