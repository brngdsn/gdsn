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
ADD brn.conf /etc/nginx/sites-enabled/

RUN apt-get update -y
RUN apt-get install -y git
RUN mkdir /etc/nginx/static
RUN git clone https://github.com/brngdsn/brn /etc/nginx/static/brn
RUN cd /etc/nginx/static/brn && git checkout master

CMD ["nginx", "-g", "daemon off;"]
