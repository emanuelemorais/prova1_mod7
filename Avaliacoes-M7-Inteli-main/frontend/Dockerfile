FROM node:latest

WORKDIR /frontend

COPY . ./
RUN npm install

# Comando para iniciar a aplicação dentro do container
CMD ["node", "server.js"]

#docker build -t {nome} .  
#docker run -p {porta}:{porta} {nome}