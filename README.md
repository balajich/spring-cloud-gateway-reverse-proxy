# spring-cloud-gateway-reverse-proxy
Simple spring cloud gateway application that acts as reverse proxy to web applications app1 and app2
# Build
In the root directory run below command

    mvn clean package
# Run
In the root directory run below commands
    
    # Run application1
    $ java -jar ./app1/target/app1-1.0.jar
    
    # Run application2
    $ java -jar ./app2/target/app2-1.0.jar

# Ports
- App1 runs on 8081
- App1 runs on 8082
- Proxy runs on 8080

# Access applications
    
    # Access application 1
    # curl http://localhost:8081/greeting
    
    # Access application 2
    # curl http://localhost:8082/greeting