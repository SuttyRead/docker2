FROM node:latest

RUN mkdir app

WORKDIR app

COPY ./build /app
COPY ./resourse /app

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]