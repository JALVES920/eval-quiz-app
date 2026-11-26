FROM nginx:stable-alpine3.24-perl

WORKDIR /etc/nginx

COPY nginx.conf /etc/nginx/nginx.conf

RUN mkdir -p /var/www/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]