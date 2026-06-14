FROM nginx:alpine

# Remove página padrão do nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia a aplicação
COPY index.html /usr/share/nginx/html/index.html

# Expõe a porta 80
EXPOSE 80

# nginx já inicia automaticamente com a imagem base
