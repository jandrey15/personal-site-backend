# FROM nginx:1.16-alpine AS development

# LABEL maintainer="web@johnserrano.co"

# COPY default.conf /etc/nginx/conf.d
# COPY backend-dev.conf /etc/nginx/conf.d
# COPY api-dev.conf /etc/nginx/conf.d
# COPY static-dev.conf /etc/nginx/conf.d

# Config production
# FROM nginx:1.16-alpine AS production
FROM nginx:1.16-alpine

LABEL maintainer="web@johnserrano.co"

COPY default-prod.conf /etc/nginx/conf.d
COPY backend-prod.conf /etc/nginx/conf.d
COPY api-prod.conf /etc/nginx/conf.d
COPY static-prod.conf /etc/nginx/conf.d
