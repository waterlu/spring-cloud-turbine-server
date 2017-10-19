# spring-cloud-turbine-server

* mvn clean package -Dmaven.test.skip docker:build
* docker run --name turbine-server -d -p 10020:10020 spring-cloud/turbine-server
* docker logs -f turbine-server
