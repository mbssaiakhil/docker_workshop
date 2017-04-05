FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
COPY index_files /usr/share/nginx/html/index_files
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
