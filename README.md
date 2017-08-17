# php-online
php在线执行代码
## how to run
```bash
composer install
bower install
docker-composer up -d

# build ace
cd public/bower/ace
npm install
make build

# docker
docker-compose build
docker-compose up -d
```
访问 http://localhost:7890/
