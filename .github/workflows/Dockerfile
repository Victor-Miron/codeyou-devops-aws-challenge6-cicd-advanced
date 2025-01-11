FROM node:16

WORKDIR /src/app

COPY package.json .

ENV PORT=3000

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "run", "start"]