# docker
```
$ docker build -t c_img .
$ docker run 
```
## Docker hub
-	Create repository in dockerhub
-	Docker login ic cli
-	Username
-	Password

  
-	Copy repo name in dockerhub and paste cli terminal
-	docker push gursingh/<repo_name:tag>
-	docker tag mywebapp:02 gursingh/web_demo:01 # change image name
-	docker pull gursingh/web_demo:01
-	docker run -it --rm -v  myvolume:/path/ <image_name> # allocate same path we use in dockerfile  (WORKDIR)
-	docker volume ls
-	docker volume inspect <volume_name>
-	docker run -v /abslute_path/file.txt:/path/file.txt --rm <image_name>
	 
## docker network 

- docker network create <network_name>

## docker-compose

-	docker-compose up
-	docker-compose down
-	docker-compose down -v  # removing all network 




