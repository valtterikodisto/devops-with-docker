FROM node:12.14.0

EXPOSE 3000

RUN git clone https://github.com/valtterikodisto/vulnerable-bank
WORKDIR vulnerable-bank

RUN npm install
CMD npm start