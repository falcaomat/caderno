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
Executa uma imagem interativamente (podendo ser bash,cmd)
```bash
docker run -it <imagem> <cmd>
```
