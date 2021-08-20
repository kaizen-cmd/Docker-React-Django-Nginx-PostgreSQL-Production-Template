# docker_tutorial/nginx_backend_server/Dockerfile

FROM nginx:1.20.1-alpine
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
