FROM nginx:stable-alpine

WORKDIR /nginx

COPY ./conf /nginx/conf
COPY ./data /nginx/data

CMD ["nginx", "-c", "/nginx/conf/nginx.conf"]
