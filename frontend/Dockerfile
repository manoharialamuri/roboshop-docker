FROM nginx:1.24.0
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html
COPY nginx.config /etc/nginx/nginx.conf/
CMD ["nginx", "-g", "daemon off;"]



