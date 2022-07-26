FROM debian:10.3-slim
LABEL maintainer="franciscomoli"

ADD entrypoint.sh /entrypoint.sh

RUN apt-get update && apt-get install -y apache2-utils
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]