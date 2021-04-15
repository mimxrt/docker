ARG FROM_BASE=jwilder
ARG NGINX_PROXY_TAG=alpine

FROM ${FROM_BASE}/nginx-proxy:${NGINX_PROXY_TAG}
#FROM jwilder/nginx-proxy:alpine

COPY uploadsize.conf /etc/nginx/conf.d/uploadsize.conf
