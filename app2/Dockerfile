FROM node

WORKDIR /app2

COPY ["package.json", "package-lock.json*", "./"] 

RUN npm install

COPY . .

EXPOSE 4001

CMD [ "npm", "start"]