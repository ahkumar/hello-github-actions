FROM debian:9.5-slim

RUN ls -l $PWD
RUN ls -l $PWD/../
COPY ./entrypoint.sh /entrypoint.sh
COPY ./entrypoint.sh /sample.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
