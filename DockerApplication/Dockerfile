FROM adoptopenjdk/openjdk15:ubi
ENV App_HOME=/user/app/
WORKDIR $App_HOME

ARG JAR_FILE=../target/*.jar
COPY ${JAR_FILE} app.jar
EXPOSE 8080
CMD ["java", "-jar", "app.jar"]