FROM ubuntu:16.04
WORKDIR /usr/app

RUN apt-get update && apt-get install -y curl 

COPY . .
RUN chmod +x ./curl-script.sh

CMD ./curl-script.sh