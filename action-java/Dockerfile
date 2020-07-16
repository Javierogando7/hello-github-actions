# Alpine Linux with OpenJDK JRE
FROM openjdk:8
# copy WAR into image
COPY HelloWorld.java . 
# compile application
RUN javac HelloWorld.java
CMD ["java", "HelloWorld"]
