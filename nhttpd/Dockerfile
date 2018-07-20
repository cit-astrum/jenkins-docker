#raghudevops/nhttpd:v1
FROM centos
RUN yum install httpd -y
RUN echo Hello V1 >/var/www/html/index.html
EXPOSE 80
CMD /usr/sbin/httpd -DFOREGROUND
