 

````
**Warning**
This templates are created only for a tech talk, therefore, far from a real-life usecase. For a realistic swarm cluster on Azure, please take a look in [here](https://github.com/MoimHossain/docker-swarm-on-azure).
````




# ARM Template - Docker swarm cluster 

This repository containers the Azure Resource manager Template that creates a 3 Nodes Docker swarm cluster.
Single master and two worker Nodes. 
The template also creates a internet facing Azure Load balancer that exposes HTTP port 80 to the world and routes the requests into the Swarm cluster where containers can serve the incoming requests.

## Contact

I have created this repository for a technical talk regarging Microservices, public Cloud and Docker swarm. Feel free to use it anyway you want. Thanks for reading.
