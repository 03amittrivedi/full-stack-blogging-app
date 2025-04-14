FROM eclipse-temurin:17-jdk-alpine
    
EXPOSE 8080
# expose the code
 
ENV APP_HOME /usr/src/app

COPY target/* $APP_HOME/app.jar

WORKDIR $APP_HOME

CMD ["java", "-jar", "app.jar"]
