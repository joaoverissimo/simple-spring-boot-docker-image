# to create jar

mvn clean install

# to build docker

docker build -t joaoverissimo/spring:0.0.3 .

docker run -p 8080:8080 joaoverissimo/spring:0.0.3



