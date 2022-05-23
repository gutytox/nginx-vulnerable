FROM nginx

COPY homer_page/ /usr/share/nginx/homer_page/
COPY login/index.html /usr/share/login/index.html
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY static/ /usr/share/nginx/
COPY .htpasswd /etc/nginx/.htpasswd
COPY fotos/ /etc/nginx/fotos/
COPY secret.txt /etc/nginx/secret.txt