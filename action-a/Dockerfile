FROM debian:9.5-slim

RUN git submodule init && git submodule update
RUN ls -l $PWD
RUN ls -l $PWD/../
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
