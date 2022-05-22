FROM nginx

COPY homer_page/ /usr/share/nginx/homer_page/
COPY login/index.html /usr/share/login/index.html
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY flag.txt /usr/share/nginx/flag.txt
COPY .htpasswd /etc/nginx/.htpasswd