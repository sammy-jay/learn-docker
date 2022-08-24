FROM node:alpine

ENV NODE_ENV=production

WORKDIR /app

COPY ["package.json","package-lock.json", "./"]

RUN npm install --omit=dev

COPY . .

EXPOSE 8000

CMD ["node", "server.js"]

