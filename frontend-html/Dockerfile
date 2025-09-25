FROM nginx:alpine

# Apaga os arquivos default do Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia todos os seus arquivos locais (HTML, CSS, JS)
COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
