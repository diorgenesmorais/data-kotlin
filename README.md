# data-kotlin

> Base de dados para projeto de estudo com Kotlin

1 - Copie o arquivo '.env.example' para '.env'

```bash
cp .env.example .env
```

2 - Defina os valores para as variáveis para o MySql no arquivo '.env'

```bash
MYSQL_DATABASE=hr
MYSQL_USER=root
MYSQL_PASSWORD="sua-senha-aqui"
```

3 - Executar usando docker compose:

```bash
docker-compose up -d
```

4 - Parar o container

```bash
docker-compose down
```

5 - Acessar o MySql do contêiner (será solicitado a senha)

```bash
docker exec -it kotlin-mysql mysql -u root -p hr
```
