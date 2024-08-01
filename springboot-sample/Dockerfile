# FROM openjdk:11
# ENV GREETING ''
# ADD /target/sample-app-0.0.1-SNAPSHOT.jar sample-app-0.0.1-SNAPSHOT.jar
# EXPOSE 8080
# CMD java -Ddw.messageGreeting=${GREETING} -jar sample-app-SNAPSHOT.jar
# #ENTRYPOINT ["java","-jar", "my-first-application-0.0.1-SNAPSHOT.jar"]
# VOLUME /tmp
FROM openjdk:11
ENV GREETING=''
ADD /target/sample-app-0.0.1-SNAPSHOT.jar sample-app-0.0.1-SNAPSHOT.jar
EXPOSE 8080
CMD ["java", "-Ddw.messageGreeting=${GREETING}", "-jar", "sample-app-0.0.1-SNAPSHOT.jar"]
VOLUME /tmp