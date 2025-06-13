FROM nginx:1.27.5

WORKDIR /etc/nginx

COPY nginx.conf .
COPY cert.pem .

EXPOSE 80/tcp
EXPOSE 443/tcp