# 🐳 Comandos Docker

Lista os containers em execução.
```bash
docker ps
```
Lista TODOS os containers (inclsuive parados)
```bash
docker ps -a
```
Cria e executa um container
```bash
docker run <imagem>
```
Executa uma imagem interativamente (I de interativo, T de TTY terminal virtual)
```bash
docker run -it <imagem> bash
```
Para um Container (Usar ID ou nome gerado pelo container)
```bash
docker stop <container>
```
Inicia um container parado
```bash
docker start <container>
```
Reinicia um Container
```bash
docker restart <container>
```
Remove um container (Precisa ter parado antes)
```bash
docker rm <container>
```
Remove um container forçando
```bash
docker rm -f <container>
```
Mostra todos os logs do container
```bash
docker logs <container>
```
Executando comando dentro do container 
```bash
docker exec -it <container> bash
```
Mostra detalhes do container
```bash
docker inspect <container>
```
