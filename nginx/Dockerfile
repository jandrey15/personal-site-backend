FROM nginx:1.16-alpine

LABEL maintainer="web@johnserrano.co"

COPY default.conf /etc/nginx/conf.d
COPY backend-dev.conf /etc/nginx/conf.d
COPY api-dev.conf /etc/nginx/conf.d
COPY static-dev.conf /etc/nginx/conf.d
