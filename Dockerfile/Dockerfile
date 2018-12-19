FROM centos:latest
RUN yum install httpd git -y -y 
RUN echo
RUN /usr/sbin/httpd $OPTIONS -DFOREGROUND
EXPOSE 80

