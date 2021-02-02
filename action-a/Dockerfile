FROM debian:9.5-slim

RUN echo $(ls -l $PWD)
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
