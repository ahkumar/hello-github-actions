FROM debian:9.5-slim

RUN ls -l $PWD
RUN ls -lR $PWD/../
COPY ./entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
