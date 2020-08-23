FROM httpd
COPY src/index.html /usr/local/apache2/htdocs/
COPY ./my-httpd.conf /usr/local/apache2/conf/httpd.conf
EXPOSE 80
CMD ["httpd-foreground"]
