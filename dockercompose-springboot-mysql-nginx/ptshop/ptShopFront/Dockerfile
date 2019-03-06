FROM java:8
ADD ptshop-8082.jar ptshopfront.jar
RUN bash -c 'touch /ptshopfront.jar'
EXPOSE 8082
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/ptshopfront.jar"]