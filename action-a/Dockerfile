FROM debian:9.0-slim

ADD entrypoint.sh /entrypoin.sh
RUN chead +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
