# CloudFaster Academy - 2022

# Informando a imagem que vamos utilizar
# Linux Alpine na última versão
FROM alpine:latest

# Instalando o Apache
RUN apk add --no-cache apache2

# Fazendo expose da porta padrão do Apache
EXPOSE 80

# Iniciando o serviço do apache na execução do container
CMD ["httpd", "-D", "FOREGROUND"]

