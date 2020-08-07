FROM nginx:stable-alpine

WORKDIR /nginx

RUN chown nginx:nginx /nginx

USER nginx

COPY ./conf /nginx/conf
COPY ./data /nginx/data

CMD ["nginx", "-c", "/nginx/conf/nginx.conf"]