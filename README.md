# Build
mvn clean package

# RUN

java -jar payara-micro-5.2021.1.jar --deploy ./target/javaee8-exemplo.war --port 8000 --contextroot ROOT
