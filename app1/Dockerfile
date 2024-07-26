FROM node

WORKDIR /app1

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

EXPOSE 4000

CMD [ "npm", "start"]