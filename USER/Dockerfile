FROM almalinux:9
RUN dnf install nginx -y
RUN useradd expense
user expense
CMD ["nginx","-g","daemon off;"]