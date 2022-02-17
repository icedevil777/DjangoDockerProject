# DjangoDockerProject
Recipe Book on Django and Docker 
# Книга рецептов

## Использование Docker

### Настройка проекта

Создайте `.env` файл в корне репозитория:



```bash
docker-compose stop
docker rmi $(docker images -q)
docker rm $(docker ps -a -q)
```

```bash
cp .env.dist .envdocker
```