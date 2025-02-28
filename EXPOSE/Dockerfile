FROM almalinux:9
RUN dnf install nginx -y
# Expose instruction is for user information. It will not change the funtionality
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]