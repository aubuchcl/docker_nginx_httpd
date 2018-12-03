FROM nginx:alpine

RUN mkdir -p /data/www
COPY default.conf /etc/nginx/conf.d/default.conf
COPY index.html /data/www 

CMD nginx -g "daemon off;"
