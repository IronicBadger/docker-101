FROM nginx
MAINTAINER Alex Kretzschmar <alex.kretzschmar@worldpay.com>

RUN apt-get update && \
    apt-get install -y \
      curl \
      nano \
      vim
     

COPY newindex.html /usr/share/nginx/html/newindex.html
COPY Dockerfile /

