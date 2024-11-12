FROM openjdk:alpine

WORKDIR /calculate/java

COPY . /calculate/java/

RUN javac calc.java

CMD ["java", "calc"]