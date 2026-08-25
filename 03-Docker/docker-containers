# 🐳 Docker Containers

Lista containers em execução
```bash
docker ps
```
Lista todos os containers (incluindo parados)
```bash
docker ps -a
```
Cria e executa um container
```bash
docker run <imagem>
```
Executa em segundo plano (detached)
```bash
docker run -d <imagem>
```
Executa interativamente
```bash
docker run -it <imagem> <cmd>
```
Para um container
```bash
docker stop <container>
```
Inicia um container parado
```bash
docker start <container>
```
Reinicia um container
```bash
docker restart <container>
```
Remove um container parado
```bash
docker rm <container>
```
Remove um container forçando
```bash
docker rm -f <container>
```
Mostra os logs do container
```bash
docker logs <container>
```
Executa comando dentro do container
```bash
docker exec -it <container> <cmd>
```
Mostra detalhes do container
```bash
docker inspect <container>
```
Exemplo: executa Nginx em background na porta 8080 e lista os containers ativos
```bash
docker run -d --name meu_nginx -p 8080:80 nginx
docker ps
```
