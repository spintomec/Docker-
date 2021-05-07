FROM debian:10.9
Label Ulysse Yadan

RUN apt-get update \
    && apt-get install -y nginx \
    && apt-get clean \

EXPOSE 8001
CMD ["nginx"]
