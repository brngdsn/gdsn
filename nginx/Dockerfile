FROM nginx

RUN mkdir /etc/nginx/sites-enabled

ADD default.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/
ADD tonic.conf /etc/nginx/sites-enabled/
ADD qckblg.conf /etc/nginx/sites-enabled/

CMD ["nginx", "-g", "daemon off;"]
