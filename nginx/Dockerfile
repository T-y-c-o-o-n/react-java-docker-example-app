FROM nginx:1.16.0-alpine as nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY proxy.conf /etc/nginx/conf.d/proxy.conf
EXPOSE 80
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]
