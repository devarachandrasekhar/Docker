#FROM almalinux:8
#CMD ["yahoo.com"]
#ENTRYPOINT [ "ping", "-c5" ]

#FROM almalinux:8
#ENTRYPOINT ["yahoo.com"]
#CMD [ "ping", "-c5" ]


FROM almalinux:8

RUN yum install nginx -y

RUN echo "Hello, welcome to Dockerfile. A way of creating own image" > /usr/share/nginx/html/hello.html

#CMD [ "nginx" , "-g" , "daemon off;" ]

ENTRYPOINT [ "nginx" , "-g" , "daemon off;" ]