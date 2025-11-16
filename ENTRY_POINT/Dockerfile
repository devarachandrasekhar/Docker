#FROM almalinux:8
#CMD ["yahoo.com"]
#ENTRYPOINT [ "ping", "-c5" ]

#FROM almalinux:8
#ENTRYPOINT ["yahoo.com"]
#CMD [ "ping", "-c5" ]


FROM almalinux:8
  # almalinux is same as centos
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hello, welcome to Dockerfile. A way of creating own image" > /usr/share/nginx/html/index.html
 #daemon off command makes our nginx running and attached to screen 
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]