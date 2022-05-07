# nuxt-docker-template

## setup

```
# docker-compose.ymlの下記を一時的にコメントアウト
# - node_modules:/src/node_modules

docker-compose up -d

docker-compose exec app sh

yarn install

docker-compose down

# docker-compose.ymlの下記のコメントアウトを戻す
# - node_modules:/src/node_modules

docker-compose up -d

docker-compose exec app sh

yarn dev -o
```
