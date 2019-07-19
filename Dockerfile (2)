FROM tomcat:latest
MAINTAINER ZB 512251296@qq.com

COPY server.xml /usr/local/tomcat/conf

RUN rm -rf /usr/local/tomcat/webapps/*

ADD ROOT.tar.gz /usr/local/tomcat/webapps/

