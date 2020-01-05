FROM ubuntu

EXPOSE 5000
ENV API_URL=http://localhost:8000

RUN apt update && apt install -y curl git
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt update && apt install -y nodejs

RUN git clone https://github.com/docker-hy/frontend-example-docker project
WORKDIR /project

RUN npm install
CMD npm start