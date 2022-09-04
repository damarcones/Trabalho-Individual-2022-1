FROM node:alpine

RUN mkdir -p /library_frontend

WORKDIR /library_frontend

COPY package.json /library_frontend/

RUN npm install

COPY . /library_frontend/

CMD ["npm", "start"]

EXPOSE 3000



