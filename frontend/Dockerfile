FROM nginx:latest
WORKDIR /usr/share/nginx/html
COPY ./build /usr/share/nginx/html
COPY ./web /etc/nginx/conf.d/
EXPOSE 80