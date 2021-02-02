FROM debian:9.5-slim

RUN ls -l $PWD
RUN ls -l $PWD/../
RUN ls -l /var/lib/docker/tmp/docker-builder*/
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
