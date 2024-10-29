FROM node:latest 
WORKDIR /app
COPY . /app/
RUN npm init -y
RUN npm install express 
EXPOSE 8080
CMD ["node","app.js"]

#RUN npm install??