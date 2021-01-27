# FROM alpine:3.7

# RUN apk update

# RUN apk add lighttpd php7-common php7-iconv php7-json php7-gd php7-curl php7-xml php7-mysqli php7-imap php7-cgi fcgi php7-pdo php7-pdo_mysql php7-soap php7-xmlrpc php7-posix php7-mcrypt php7-gettext php7-ldap php7-ctype php7-dom
# RUN rc-service lighttpd start && rc-update add lighttpd default
# RUN apk add wget php5-mysql mysql mysql-client php5-zlib
# RUN /etc/init.d/lighttpd restart
# RUN mkdir -p /usr/share/webapps/
# COPY srcs/wordpress /usr/share/webapps
# RUN chown -R lighttpd /usr/share/webapps/
# RUN ln -s /usr/share/webapps/wordpress/ /var/www/localhost/htdocs/wordpress


FROM alpine:3.7

RUN apk update
RUN apk add nginx openrc 
RUN mkdir /run/nginx/
#RUN echo "its works ;)" > /www/index.html
RUN touch /run/nginx/nginx.pid
#COPY src/start.sh ./
# RUN  mv /etc/nginx/nginx.conf /etc/nginx/nginx.conf.orig
# COPY srcs/nginx.conf  /etc/nginx/

# start nginx server
#CMD sh start.sh


