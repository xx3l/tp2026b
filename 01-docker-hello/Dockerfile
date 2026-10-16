FROM nginx
RUN apt update && apt install -y vim
COPY index.html /usr/share/nginx/html/
COPY images.jfif /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/
