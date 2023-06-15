FROM nginx:latest

COPY html/ /usr/share/nginx/html

# WORKDIR /app

# RUN apt-get update && apt-get install vim -y

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "nginx", "-g", "daemon off;" ]