#raghudevops28/nhttpd:v2
FROM centos
RUN yum install httpd -y
RUN echo Hello V2 >/var/www/html/index.html
EXPOSE 80
CMD /usr/sbin/httpd -DFOREGROUND
