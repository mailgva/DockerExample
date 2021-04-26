mvn clean package

// java -jar target/spring-boot-web.jar

sudo docker build -t spring-boot:1.0

// sudo docker run -d -p 8080:8080 -t spring-boot:1.0

sudo docker login -u mailgva

sudo docker image tag spring-boot:1.0 mailgva/spring-boot:1.0

sudo docker image push mailgva/spring-boot:1.0

sudo docker pull mailgva/spring-boot:1.0

sudo docker run -d -p 80:8080 -t spring-boot:1.0

good example!
