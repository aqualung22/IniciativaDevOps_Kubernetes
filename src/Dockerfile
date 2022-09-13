FROM node:16.15.0
WORKDIR /app
COPY ./package*.json ./
RUN apt update
RUN apt-get install npm --yes
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

