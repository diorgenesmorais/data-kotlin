# data-kotlin

> Base de dados para projeto de estudo com Kotlin

1 - Renomei o arquivo '.env.example' para '.env'

```bash
mv .env.example .env
```

2 - Defina uma senha para o MySql no arquivo '.env'

```bash
MYSQL_PASSWORD="sua-senha"
```

3 - Executar do docker compose:

```bash
docker-compose up -d
```

4 - Parar o container

```bash
docker-compose down
```
