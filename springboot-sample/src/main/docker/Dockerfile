FROM openjdk

ENV GREETING ''

ADD /target/my-first-application-0.0.1-SNAPSHOT.jar my-first-application-0.0.1-SNAPSHOT.jar
EXPOSE 8080
CMD java -Ddw.messageGreeting=${GREETING} -jar my-first-application-0.0.1-SNAPSHOT.jar
VOLUME /tmp