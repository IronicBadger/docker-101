FROM nginx
MAINTAINER Alex Kretzschmar <alex.kretzschmar@worldpay.com>

RUN apt-get update && \
    apt-get install -y \
      vim \
      nano

COPY newindex.html /usr/share/nginx/html/index.html
COPY Dockerfile /

