# Version 0.0.1
FROM fiadliel/java8-jre

MAINTAINER xutao "xutao6936@163.com"

# ��������
ENV WORK_PATH /home/project/dockerdemo
#ENV APP_NAME @project.build.finalName@.@project.packaging@
#ENV APP_VERSION @project.version@

EXPOSE 8761

#USER
#USER user:group

#VOLUME
VOLUME ["/home/project", "/tmp/data"]

#ADD

#COPY
COPY $APP_NAME $WORK_PATH/

#LABEL
#STOPSIGNAL
#ARG
#ONBUILD

# WORKDIR
WORKDIR $WORK_PATH

# ENTRYPOINT 
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom"]

# CMD
CMD ["-jar", "eureka-server.jar"]
