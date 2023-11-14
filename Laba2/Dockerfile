FROM alpine:latest
RUN apk update
RUN apk add nginx
COPY nginx.conf /etc/nginx/nginx.conf 
COPY index.html /usr/share/nginx/html
EXPOSE 8080
CMD ["nginx"]
