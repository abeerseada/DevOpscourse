
## Services

- **mongo**: Runs the latest MongoDB image and stores data in a Docker volume.
- **node**: Runs the Node.js application, which connects to the MongoDB database.

The environment `mongo_url` is set to `mongodb://mongo:27017/testdb`

## Setup

1. **Add your Node.js application** in the `src` directory.

2. **Build and start the services**:
    ```
    docker-compose up --bulid
    ```

    This command will:
    - Pull the latest MongoDB image and start a container
    - Build the Node.js image from the `Dockerfile` and start a container

3. **Access the Node.js Application**:
    - The Node.js app will be at [http://localhost:8080]
    - MongoDB will be  at `localhost:27017`.



http://localhost:8080/insert 
