# Digital Bank

Open source : https://github.com/MungThai/digitalbank.git
git clone https://github.com/MungThai/digitalbank.git

Digital Bank is a sample HTML5 Spring Boot application developed for exploratory purposes.

The application is configured for HTTP to listen on port 8080 or for HTTPS to listen on port 8443.

Docker run command: docker run -d -p 8080:8088 -p 8443:8443 digisic/digitalbank:latest

User Interface: "http://localhost:8080/bank" or "https://localhost:8443/bank"

Default User: jsmith@demo.io / Demo123!

For tagged versions earlier than 2.1.0.8, the application is configured without SSL and listens on port 8080.

Docker run command: docker run -d -p 8080:8080 digisic/digitalbank:tag

User Interface: http://localhost:8080/bank

Default User: jsmith@demo.io / Demo123