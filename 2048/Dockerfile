FROM ubuntu

RUN apt-get update && apt-get install -y git nginx
RUN git clone https://github.com/gabrielecirulli/2048 /app
RUN cp -r /app/* /var/www/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
