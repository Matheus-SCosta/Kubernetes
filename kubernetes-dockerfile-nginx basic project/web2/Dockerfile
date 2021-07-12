FROM nginx:latest

COPY index.html /usr/share/nginx/html
WORKDIR /etc/nginx/
COPY nginx.conf conf.d/
RUN rm -rf conf.d/default.conf
