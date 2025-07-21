FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
# Ensure nginx.conf exists in the build context before adding
ADD nginx.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/