FROM nginx:latest
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ENV CATALOGUE_HOST="catalogue"

