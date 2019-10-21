FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD springcloudconfig-1.0.0.jar app.jar
ADD startup.sh startup.sh
RUN chmod +x startup.sh
CMD ["./startup.sh"]