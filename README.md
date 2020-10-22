# ADO Vistualização

## Como usar:
1. cmd diretório da aplicação
2. docker build -t canejo/hello-world .
3. docker run -it --rm -d -p 8080:80 --name canejo/hello-world

## Ou direto do DockerHub:
docker run --rm -p 8080:80 canejo/hello-world
