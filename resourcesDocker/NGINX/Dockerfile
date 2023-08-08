FROM ubuntu:latest

EXPOSE 80

RUN apt-get update && \
    apt-get install nginx -y && \ 
    apt-get clean && rm -rf /vat/lib/apt/lists/*

CMD ["nginx", "-g", "deamon off;"]

