FROM nginx:1.27.1-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d


EXPOSE 80

CMD ["nginx-debug", "-g", "daemon off;"]
