FROM nginx:latest

COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf


CMD ["nginx", "-g", "daemon off;"]