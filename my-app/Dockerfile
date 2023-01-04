FROM anapsix/alpine-java
RUN adduser -D nonroot
USER nonroot
ARG VER
ADD target/my-app-$VER.jar /home/myjar.jar
CMD ["java","-jar","/home/myjar.jar"]
