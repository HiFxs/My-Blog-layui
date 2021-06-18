FROM java:8
VOLUME /tmp
ADD my-blog-layui-1.0.0-SNAPSHOT.jar /test.jar
EXPOSE 28084
ENTRYPOINT ["java","-Djava.sercurity.egd=file:/dev/./urandom","-jar","/test.jar"]
