# eureka-start

### notes
- dependencies needed are: spring-cloud-starter-netflix-eureka-server and spring-cloud-dependencies
- in properties file: set both eureka.client.register-with-eureka and eureka.client.fetch-registery to false to avoid registering this service to itself.
