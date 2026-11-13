FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ONBUILD COPY src/ /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]   
 ## on build cant run  we can test the crate new folder