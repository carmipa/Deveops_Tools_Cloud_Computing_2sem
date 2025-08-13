# Usa a imagem oficial do nginx
FROM nginx:alpine

# Remove a configuração padrão do nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia seus arquivos HTML/CSS/JS para o diretório padrão do nginx
COPY . /usr/share/nginx/html

# Expõe a porta 80
EXPOSE 80