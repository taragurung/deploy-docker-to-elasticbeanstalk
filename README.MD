## How to deploy the dockerized application to the ElasticBeanStalk

1. Create a Dockerfile (to build image that will be used the ElasticBeanstalk)
2. Create a Dokerrun.aws.json file (guides ElasticBeanStalk on what to run and deployment settings,)

Note: 
Don't use the image tag if we are using the Dockerfile. Because the ElasticBeanstalk will use the Dockerfile available to build the image and use the same image to run as described (other settings of docker like ports and volumes)




### Getting image from the External repository:
If we have the images in External repo than we can simply use that instead of writing the the Dockerfile and simply use the Dockerrun.aws.json, where we can simply put the image to use.



