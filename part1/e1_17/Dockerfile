FROM ubuntu

RUN apt update && apt install -y curl git build-essential nano
RUN curl -sL https://deb.nodesource.com/setup_12.x | bash
RUN apt update && apt install -y nodejs

RUN npm install -g typescript

CMD ["/bin/bash"]