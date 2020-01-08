FROM nginx:1.14

ADD conf/nginx.conf /etc/nginx/
ADD conf/conf.d /etc/nginx/conf.d/

RUN usermod -u 1000 www-data

CMD ["nginx"]

EXPOSE 80 443
