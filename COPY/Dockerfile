FROM almalinux:9
RUN dnf install nginx -y
COPY index.html /usr/shared/nginx/index.html
CMD ["nginx", "-g", "daemon off;"]
