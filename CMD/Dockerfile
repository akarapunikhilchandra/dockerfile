FROM almalinux:8
RUN yum install nginx -y 
RUN echo "HI" > /opt/hello.txt 
CMD ["nginx", "-g", "daemon off;"]