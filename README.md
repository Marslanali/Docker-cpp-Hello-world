# Docker-cpp-Hello-world
Deploying Simple C++ applications using Docker 


### Docker installation

**On Debian and Ubuntu:**


### Set up the docker repository.

```
sudo apt-get update
sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```

### Install Docker Container

```
sudo apt-get update
sudo apt-get install docker-ce
```

### Verify the installation

```
sudo docker run hello-world
```


### Deploying a simple Hello World C++ applications using Docker


The First Docker Container: The Base Build Container
