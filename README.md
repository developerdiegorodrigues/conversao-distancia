# Conversão de distâncias

> Aplicação web python com framework flask em ambiente docker


Aula 1 do *Desafio DevOps & Cloud* ministrado pelo professor *Fabricio Veronez*

Projeto disponível no Docker Hub através do [endereço](https://hub.docker.com/repository/docker/devdiegorodrigues/conversao-distancia/general)


```bash
# Docker Hub
docker container run -d -p 8181:5000 devdiegorodrigues/conversao-distancia:v1

# Local
docker build -t conversao-distancia
docker run -d -p 8181:5000 '<CONTAINER_ID>'
```

> [!TIP]
> Ao rodar a aplicação ela estará disponível através de localhost:8181

