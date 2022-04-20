FROM httpd:2.4
RUN apt update
RUN apt install net-tools
COPY server.crt /usr/local/apache2/conf/server.crt
COPY server.key /usr/local/apache2/conf/server.key
EXPOSE 443
