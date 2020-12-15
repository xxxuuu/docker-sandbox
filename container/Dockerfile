FROM gcc:9.3.0
LABEL maintainer="XUQING"
RUN adduser sandbox -u 1111 -h /sandbox -D
COPY sandbox /usr/sbin/
CMD while true; do sleep 1; done
