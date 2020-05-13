# maven-project

Simple Maven Project

- CI/CD pipeline using Git, Jenkins and Maven
- Integrating tomcat server in CI/CD pipeline
- Integrating Docker in the Jenkins CI/CD pipeline
???? exporter dans mon private repo|Operationalize-a-Machine-Learning-Microservice-API/upload_docker.s
	- Download a docker image from hub.docker.com 
		`docker pull tomcat:latest`
	- Create/run/start a docker container from image
		`docker run -d --name docker-container -p 8080:8080 tomcat:latest`
		`docker container start docker-container` #docker-container is our container name
	- Integrating Docker with Jenkins
	docker login &&\
    docker image tag docker-container jmntepp/nteppcapston
	
	docker image push jmntepp/nteppcapston
	- Copy the war file to the docker container
		- Create Dockerfile
			`docker build -t devops-project .`
	- Create container
	`docker run -d --name devops-container7 -p 8081:8080 devops-project`

