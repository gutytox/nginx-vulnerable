# Vulnerable-nginx

Esta es una aplicaciòn intencionalmente vulnerable basada en [https://github.com/detectify/vulnerable-nginx](https://github.com/detectify/vulnerable-nginx), esta especialmente diseñado para la charla Nginx Security de [https://exploitland.com/](https://exploitland.com/)ExploitLand.com

Gran parte de las configuraciones inseguras de Nginx se tomaron en base a la siguiente publicacion: [https://blog.detectify.com/2020/11/10/common-nginx-misconfigurations/](https://blog.detectify.com/2020/11/10/common-nginx-misconfigurations/)

## Installation

Requires docker

```bash
cd vulnerable-nginx
docker-compose up -d
```

## Usage

Acceder a http://127.0.0.1/