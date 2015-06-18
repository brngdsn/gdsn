FROM nginx

RUN mkdir /etc/nginx/sites-enabled

ADD default.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/
ADD tnc.conf /etc/nginx/sites-enabled/
ADD qckblg.conf /etc/nginx/sites-enabled/
ADD nfnt.conf /etc/nginx/sites-enabled/
ADD clck.conf /etc/nginx/sites-enabled/
ADD trnscld.conf /etc/nginx/sites-enabled/
ADD hrvrd.conf /etc/nginx/sites-enabled/

CMD ["nginx", "-g", "daemon off;"]
