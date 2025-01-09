FROM node:8-alpine
WORKDIR /
COPY /package*.json ./
RUN npm install --only=production
COPY . .
ENTRYPOINT ["node", "--inspect=9229", "app.js"]
