# <center>Reproducible computational environments using containers</center>

<center>
![image](./images/apptainer-primary.png){width="300"}
</center>

!!! circle-info ""
    
    This lesson provides an introduction to using the [Apptainer container platform](https://apptainer.org/). Apptainer is particularly suited to running containers on infrastructure where users don’t have administrative privileges, for example shared infrastructure such as High Performance Computing (HPC) clusters.

    This lesson will introduce Apptainer from scratch showing you how to run a simple container and building up to creating your own containers and running parallel scientific workloads on HPC infrastructure.


!!! calendar-days "Schedule"

    1. [Getting Started with Containers](./1.getting-started-with-containers.md)	
        - What is a container and why might I want to use it?
    2. [The Container Cache	Why does Apptainer use a local cache?](./2.container-cache.md)
        - Where does Apptainer store images?
        - How do I configure my cache ?
    3. [Using containers to run commands](./3.using-containers-to-run-commands.md)	
        - How do I use container software on the cluster?
        - How do I run different commands within a container?
        - How do I access an interactive shell within a container?
    4. [Files in containers](./4.files-in-containers.md)	
        - How do I make data available in a container?
        - What data is made available by default in a container?
    
    5. [Creating Container Images](./5.creating-container-images.md)	
        - How can I make my own Apptainer container images?
        - How do I document the ‘recipe’ for a Apptainer container image
    6. [Building Container Images](./6.building-container-imaged.md)	
        - How do I create my own Apptainer images?