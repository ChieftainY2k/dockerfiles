FROM codete/php5

MAINTAINER Codete <docker@codete.com>

RUN (curl -sS https://getcomposer.org/installer | php) && \
    chmod +x composer.phar && \
    mv composer.phar /usr/local/bin/composer

VOLUME ["/srv"]

WORKDIR /srv

ENTRYPOINT ["composer"]
