# Example java service for ReportPortal

Example of creating simple additional service on java using Spring Boot for ReportPortal. Can be used 
as getting started sample. The service info is specified in [bootstrap.yaml](https://github.com/reportportal/example-service-java/blob/master/src/main/resources/bootstrap.yaml)

### Communication with ReportPortal

As ReportPortal has a microservice based architecture it uses Service Discovery with Consul.
To activate Consul Service Discovery you can follow the next guide: 
[Service Discovery with Consul](http://cloud.spring.io/spring-cloud-consul/multi/multi_spring-cloud-consul-discovery.html) 
or go through [example](https://github.com/reportportal/example-service-java/blob/master/src/main/resources/application.yaml).
There are a few more configuration extensions for running service on 
[dev-machine](https://github.com/reportportal/example-service-java/blob/master/src/main/resources/application-dev-mac.yaml),
and in [docker](https://github.com/reportportal/example-service-java/blob/master/src/main/resources/application-docker.yaml).