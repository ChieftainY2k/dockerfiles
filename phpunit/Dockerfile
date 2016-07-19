FROM codete/php5

MAINTAINER Codete <ci@codete.com>

RUN wget https://phar.phpunit.de/phpunit.phar && \
    chmod +x phpunit.phar && \
    mv phpunit.phar /usr/local/bin/phpunit

WORKDIR /srv

ENTRYPOINT ["phpunit"]
