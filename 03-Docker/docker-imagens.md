# 🐳 Docker Imagens

Lista todas as imagens locais
```bash 
docker images
```
Baixa uma imagem do Docker Hub
```bash
docker pull <imagem>
```
Busca imagens no Docker Hub
```bash
docker search <termo>
```
Mostra detalhes de uma imagem
```bash
docker inspect <imagem>
```
Remove uma imagem
```bash
docker rmi <imagem> 
```
Remove uma imagem forçado
```bash
docker rmi -f <imagem>
```
Remove imagens não utilizadas
```bash
docker image prune
```
Marca uma imagem com novo nome
```bash
docker tag <img> <novo:tag>
```
