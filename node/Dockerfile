FROM node:latest 
WORKDIR /app
COPY . /app/

# Copy package.json and package-lock.json (if available)
COPY package*.json ./

# Install app dependencies
RUN npm install
EXPOSE 8080
CMD ["node","app.js"]