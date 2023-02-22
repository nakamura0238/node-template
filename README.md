# nodeプロジェクト テンプレート
### 使用コンテナ
- nginx
- node.js
- mysql
---
### コンテナ作成
```
docker-compose build
```

### Next.js
```
docker-compose run --rm front sh -c 'npx create-next-app --typescript .; npx eslint --init'
```

### Express
```
```

### コンテナ起動
```
docker-compose up -d
```

### .env
```
# nginx
NGINX_PORT=

# api
API_PORT=

# front
FRONT_PORT=
NODE_ENV=development

# db
DB_PORT=
MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE=
MYSQL_USER=
MYSQL_PASSWORD=

# phpmyadmin
PHP_MY_ADMIN_PORT=
```