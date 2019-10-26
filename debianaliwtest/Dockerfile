FROM debian
RUN echo 'deb http://deb.debian.org/debian testing main' >> /etc/apt/sources.list
RUN sed -i 's/deb.debian.org/mirrors.aliyun.com/g' /etc/apt/sources.list
RUN apt-get update
CMD bash


