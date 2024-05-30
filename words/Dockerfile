FROM ubuntu

WORKDIR /words

RUN apt-get update && apt-get install -y maven

COPY . .

RUN mvn verify

CMD ["java","-Xmx8m", "-Xms8m", "-jar", "target/words.jar"]