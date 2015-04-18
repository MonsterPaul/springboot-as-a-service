# springboot-as-a-service
Run spring-boot as a service (linux)

# How to use it

- copy the script file in /etc/init.d
- run command chmod a+x /etc/init.d/springboot
- to use it: 
  - (sudo) service springboot start /path/to/target/yourApplication.jar
  - (sudo) service springboot stop /path/to/target/yourApplication.jar
  - (sudo) service springboot restart /path/to/target/yourApplication.jar
