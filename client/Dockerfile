# Client/Dockerfile
FROM node:21.6
WORKDIR /app
COPY package*.json ./
RUN npm install -g vite
RUN npm install
COPY . .
EXPOSE 5173
CMD [ "npm","run", "dev"]

