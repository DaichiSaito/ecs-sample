FROM nginx:alpine

# これは不要かも
RUN rm -f /etc/nginx/conf.d/*

COPY nginx.conf /etc/nginx/conf.d/rails.conf

CMD /usr/sbin/nginx -g 'daemon off;'