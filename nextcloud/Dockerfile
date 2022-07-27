FROM nextcloud:23-fpm

RUN set -ex; \
    \
    apt-get update; \
    apt-get install -y --no-install-recommends \
        smbclient \
    ; \
    rm -rf /var/lib/apt/lists/*; \
