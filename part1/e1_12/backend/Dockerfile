FROM ubuntu

EXPOSE 8000
ENV FRONT_URL=http://localhost:5000

RUN apt update && apt install -y curl git
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt update && apt install -y nodejs

RUN git clone https://github.com/docker-hy/backend-example-docker backend
WORKDIR /backend

RUN npm install
CMD npm start