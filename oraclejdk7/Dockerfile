# java7
#
# VERSION               1.0

FROM centos:latest

MAINTAINER makefu <83368981@qq.com>

LABEL Description="Oracle java7 on Centos" Basic usage="docker build -t makefu/java7 . \ndocker run -d makefu/java7" Version="1.0"

RUN cd /usr

RUN curl -v -j -k -L -H "Cookie: oraclelicense=accept-securebackup-cookie" http://120.198.244.31:9999/download.oracle.com/otn-pub/java/jdk/7u79-b15/jdk-7u79-linux-x64.rpm?AuthParam=1433389691_f2c08d517eb535558703fffc91c210b1 > jdk-7u79-linux-x64.rpm

RUN rpm -ivh jdk-7u79-linux-x64.rpm

CMD ["java", "-version"]
