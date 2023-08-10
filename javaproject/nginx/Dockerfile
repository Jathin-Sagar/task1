FROM nginx:alpine
RUN apk update && apk add --no-cache iputils
#COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html
EXPOSE 80
CMD ["nginx","-g","daemon off;"]

