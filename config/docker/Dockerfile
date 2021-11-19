FROM gabrielpcruz/npf:php73
ARG DEBIAN_FRONTEND=noninteractive

COPY nginx/fastcgi-php.conf /etc/nginx/snippets/fastcgi-php.conf

RUN apt-get update -y && apt-get install php7.3-soap -y