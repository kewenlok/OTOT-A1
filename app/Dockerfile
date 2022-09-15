FROM node:16-slim
WORKDIR /app
COPY package*.json ./
RUN npm install --quiet
EXPOSE 3000/tcp
COPY . .