FROM nginx
RUN http_proxy=http://172.27.100.5:4444 https_proxy=http://172.27.100.5:4444 apt update 
RUN http_proxy=http://172.27.100.5:4444 https_proxy=http://172.27.100.5:4444 apt install -y vim
COPY index.html /usr/share/nginx/html/
COPY images.jfif /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/
