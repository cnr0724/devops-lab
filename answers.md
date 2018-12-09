# Answers

Lastname: Nuree
Firstname: Choi

## 2.2
command: docker run zoo_nuree

## 2.3
question: It's because the port needed to access the service is not published.
command: docker run -P zoo_nuree

## 2.5
question: According to the docs about the docker, this information is provided; 'You need to include the namespace for Docker Hub to associate it with your account. The namespace is the same as your Docker Hub account name. You need to rename the image to YOUR_DOCKERHUB_NAME/docker-whale.' So I renamed the image to nureechoi/zoonuree, tagging it.
command:docker push zoonuree nureechoi/zoonuree

## 2.6
command:

question:
command:

command:

## 2.7
question: The started containers can be seen by CLI command docker_ps. By default setting, it shows the containers that are already started.
question: The name is the same with the one I've made previously.
command: docker ps

command: docker rename zoonuree zoo_manage_nc, docker restart zoo_manage_nc

## 2.8
question: Windows Server 2012 R2 Datacenter
output: Operating System: Windows Server 2012 R2 Datacenter
OSType: windows

## 3.1
command:

## 3.4
command:
command:
