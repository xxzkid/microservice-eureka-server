FROM java:8
VOLUME /tmp
ADD microservice-eureka-server-0.0.2-SNAPSHOT.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8761
ENTRYPOINT ["java","-jar","/app.jar"]