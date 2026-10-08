FROM nginx:latest
LABEL maintainer="team" description="WEB server (www.example.com)"
COPY site/ /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
