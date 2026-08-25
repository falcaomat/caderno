# 🐳 Docker Redes

Lista redes
```bash
docker network ls
```
Cria uma rede
```bash
docker network create <nome>
```
Mostra detalhes da rede
```bash
docker network inspect <nome>
```
Conecta container à rede
```bash
docker network connect <rede> <container>
```
Desconecta container da rede
```bash
docker network disconnect <rede> <container>
```
Remove uma rede
```bash
docker network rm <nome>
```
Remove redes não utilizadas
```bash
docker network prune
```
Exemplo: cria uma rede e executa um container conectado a ela
```bash
docker network create minha_rede
docker run -d --name app --network minha_rede nginx
```
