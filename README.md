# springboot-aws-deploy

This is a sample microservice to deploy it on AWS ECS.

To build automated AWS CodePipeline and deploy microservice to AWS ECS, follow tutorial as shown in video :

Video Link :https://youtu.be/ARGmrYFfv44

Health Check command for AWS Task definition : 
```
CMD-SHELL,curl -f http://localhost:8080/actuator/health || exit 1
```


Prerequisite :
1. AWS acconunt.
2. Git and docker installed on the machine.
3. Docker should be started before building docker image.
4. And your favourite code editor 

