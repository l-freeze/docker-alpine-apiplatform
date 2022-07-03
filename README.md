# clone 
```
git clone https://github.com/l-freeze/docker-alpine-apiplatform
```

# .env
任意で書き換え可能だが、操作内容は書き換えない事を前提としている
```
APP_NAME=lfreeze
MYSQL_DATABASE=lfreeze
MYSQL_USER=lfreeze
MYSQL_PASSWORD=lfreeze
MYSQL_ROOT_PASSWORD=lfreeze
```

```
docker-compose down --volumes
docker-compose up -d --build
```


http://localhost/api
