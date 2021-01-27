FROM alpine:3.7

RUN apk update \
    apk add nginx openrc 

COPY srcs/start.sh ./ 
# RUN  mv /etc/nginx/nginx.conf /etc/nginx/nginx.conf.orig
# COPY srcs/nginx.conf  /etc/nginx/

# start nginx server
CMD sh start.sh
#RUN   adduser -D -g 'www' www 
#RUN    mkdir /www 
# RUN    chown -R www:www /var/lib/nginx 
# RUN   chown -R www:www /www

# RUN  mv /etc/nginx/nginx.conf /etc/nginx/nginx.conf.orig
# COPY srcs/nginx.conf  /etc/nginx/
# RUN   service nginx start 
