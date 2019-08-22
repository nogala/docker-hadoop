FROM nogala/hadoop-base:2.8.5

MAINTAINER Norberto Garcia <nogala@gmail.com>

HEALTHCHECK CMD curl -f http://localhost:8088/ || exit 1

ADD run.sh /run.sh
RUN chmod a+x /run.sh

EXPOSE 8088

CMD ["/run.sh"]
