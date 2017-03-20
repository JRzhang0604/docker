FROM nginx:latest

MAINTAINER Mahmoud Zalt <mahmoud@zalt.me>

ADD nginx.conf /etc/nginx/
COPY sites/*.conf /etc/nginx/sites-available/

CMD ["nginx"]

EXPOSE 80 443