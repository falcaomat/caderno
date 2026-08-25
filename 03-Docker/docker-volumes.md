# 🐳 Docker Volumes

Lista volumes
```bash
docker volume ls
```
Cria um volume
```bash
docker volume create <nome>
```
Mostra detalhes do volume
```bash
docker volume inspect <nome>
```
Remove um volume
```bash
docker volume rm <nome>
```
Remove volumes não utilizados
```bash
docker volume prune
```
Exemplo: cria um volume chamado "dados" e usa dentro do container
```bash
docker volume create dados
docker run -v dados:/app/data nginx
```