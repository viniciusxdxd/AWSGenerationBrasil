FROM ubuntu/nginx:latest

LABEL maintainer="Meu primeiro Projeto Docker"

RUN apt update && apt upgrade -y

COPY ./pokedex /var/www/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
