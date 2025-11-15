Spring Boot Docker Kubernetes | Spring Boot Kubernetes Microservices | Docker Kubernetes tutorial

https://www.youtube.com/watch?v=SzbeDqBSRkc

Step1: Create a Spring boot project, and run locally.
Step2: Create a Dockerfile and write commands in it to create the image of project and push in dockerhub repository/container
Step3: Create a local image of docker (cmd: docker build -t docker-demo .)
Step4: Push the local image in dockerhub
	   cmd: for tag: docker tag docker-demo abhishekhartiwari/docker-demo
	   cmd: for push:docker push abhishekhartiwari/docker-demo
Step5: Delete the images from local now(because image is present on cloud)	
	   cmd: docker rmi abhishekhartiwari/docker-demo docker-demo
Step6: Pull the image from dockerhub
	   cmd: docker run -p 8080:8080 abhishekhartiwari/docker-demo
Step7: Run project using image from dockerhub	   
	   
