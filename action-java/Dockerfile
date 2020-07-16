# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine
# copy WAR into image
COPY HelloWorld.java . 
# compile application
CMD ["javac", "HelloWorld.java"]
RUN javac --version
# run application with this command line
CMD ["java", "HelloWorld"]
