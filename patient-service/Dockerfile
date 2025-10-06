FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=dev
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]