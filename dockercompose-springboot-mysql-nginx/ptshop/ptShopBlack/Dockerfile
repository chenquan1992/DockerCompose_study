FROM java:8
ADD ptshopblack-8084.jar ptshop.jar
RUN bash -c 'touch /ptshop.jar'
EXPOSE 8084
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/ptshop.jar"]