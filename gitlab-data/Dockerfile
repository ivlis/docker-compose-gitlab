FROM busybox

MAINTAINER ivlis

RUN mkdir -p /home/git/data
RUN mkdir -p /var/lib/redis
RUN mkdir -p /var/lib/mysql

VOLUME /home/git/data
VOLUME /var/lib/redis
VOLUME /var/lib/mysql

CMD /bin/true
