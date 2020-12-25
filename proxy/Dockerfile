FROM httpd:2.4

RUN mkdir -p /var/cache/apache2/mod_cache_disk
RUN chown -R daemon:daemon /var/cache/apache2/mod_cache_disk
RUN chmod -R 777 /var/cache/apache2/mod_cache_disk

VOLUME cache:/var/apache/apacche2/mod_cache_disk

EXPOSE 80

