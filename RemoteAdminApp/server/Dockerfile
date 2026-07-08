FROM node:20-alpine

WORKDIR /app

COPY . .
RUN npm install --omit=dev


EXPOSE 3001

CMD ["node", "src/server.js"]
