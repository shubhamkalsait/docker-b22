# INSTRUCTION ARG

FROM centos:7

LABEL developer="shubham kalsait"

RUN yum install httpd -y 
RUN echo "<h1> Hello world" > /var/www/html/index.html

EXPOSE 80

CMD httpd -DFOREGROUND
# ENTRYPOINT