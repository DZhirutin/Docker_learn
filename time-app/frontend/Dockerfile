FROM node:alpine
WORKDIR /app
EXPOSE 3000
COPY package*.json ./
RUN npm install --no-fund
COPY . .
CMD [ "npm", "run", "dev" ]