# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine
# copy WAR into image
COPY HelloWorld.java . 
# compile application
RUN java -version
# run application with this command line
CMD ["java", "HelloWorld"]
