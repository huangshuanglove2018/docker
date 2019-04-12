# Pull base image  
FROM centos:7.6.1810  
  
LABEL  description="458419455@qq.com" \
       jdk_version="openjdk:1.8.0._201"  
COPY   jdk1.8.0_121 /opt/jdk1.8.0_121   
ARG    JAVA_HOME="/opt/jdk1.8.0_121"
ENV    JAVA_HOME=$JAVA_HOME  \
       CLASSPATH=".:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar" \
       PATH="$PATH:$JAVA_HOME/bin"
  
  
  
