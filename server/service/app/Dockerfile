FROM node:lts-hydrogen

ENV DATABASE_URL=$(DATABASE_URL)

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

CMD [ "npm", "start"]