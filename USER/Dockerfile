FROM almalinux:9
RUN dnf install nginx -y
RUN useradd expense
USER expense
RUN useradd newuser
CMD ["nginx","-g","daemon off;"]