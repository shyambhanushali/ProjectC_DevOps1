FROM owasp/modsecurity:3.0.6-alpine
ENV PROXY_SSL=on
ENV BACKEND=http://172.16.1.2
COPY server.crt /usr/local/apache2/conf/server.crt
COPY server.key /usr/local/apache2/conf/server.key
EXPOSE 443