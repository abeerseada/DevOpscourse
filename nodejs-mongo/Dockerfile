FROM node:20

WORKDIR /user/src/app

COPY . .

RUN npm init -y 
RUN npm install
RUN npm install express mongoose

EXPOSE 5001

CMD ["node", "app.js"]