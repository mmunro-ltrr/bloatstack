FROM debian:stretch-20190228

RUN set -e \
  && apt-get update \
  && apt-get install -y \
    apache2 \
    expect \
    libapache2-mod-php \
    openjdk-8-jdk \
    openssh-client \
    php \
    php-curl \
    php-pgsql \
    php7.0-mbstring \
    php7.0-xml \
    php7.0-zip \
    postgis \
    postgresql-server-dev-9.6 \
    sudo \
    supervisor \
    wget \
  && rm -r /var/lib/apt/lists/*
