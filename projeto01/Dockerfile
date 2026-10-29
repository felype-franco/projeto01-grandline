#imagem base
FROM nginx:alpine3.17

#metadados e documentação
LABEL maintainer = "Felype Franco <felypefranco91@gmail.com>"
LABEL description = "Imagem web para o projeto DevOps"

#diretorio de trabalho
WORKDIR /usr/share/nginx/html

#copia o arquivo da origem
COPY /projeto01-grandline/projeto01/index.html .

#expoe a porta web
EXPOSE 80

#comando de inicialização após o container subir
CMD ["nginx", "-g", "daemon off;"]