FROM ubuntu:24.04
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update && apt install apache2 -y

EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
