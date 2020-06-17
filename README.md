php5.6-fpm-alpine

docker build  --rm  -t 3creatives/php5.6-fpm-alpine:v1.0.0 -f Dockerfile .

Push to Docker Hub
===================

docker login
docker tag 3creatives/php5.6-fpm-alpine:v1.0.0 3creativessas/php5.6-fpm-alpine:v1.0.0
docker push 3creativessas/php5.6-fpm-alpine:v1.0.0