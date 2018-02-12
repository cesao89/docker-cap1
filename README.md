# Node.js with Docker

Projeto executado como aprendizado no curso de Docker da Alura.

# Docker

Docker rodando com imagem do Node

##### Como iniciar

Iniciando com o **DOCKER** com compartilhamento do volume
```sh
$ docker build -t cesao89/node .
$ docker run --name node -d -p "80:3000" cesao89/ralcontrol
```