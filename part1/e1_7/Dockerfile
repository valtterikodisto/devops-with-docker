FROM ubuntu

WORKDIR /curler/
RUN apt update && apt install -y curl
COPY script.sh ./
RUN chmod +x script.sh
CMD ["./script.sh"]