php5.6-fpm-alpine

docker build  --rm  -t 3creatives/php5.6-fpm-alpine:latest -f Dockerfile .

Push to Docker Hub
===================

docker login
docker tag 3creatives/php5.6-fpm-alpine:latest 3creativessas/php5.6-fpm-alpine:latest
docker push 3creativessas/php5.6-fpm-alpine:latest