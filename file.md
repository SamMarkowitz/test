#Content

The slang-content repository contains ready-made Slang flows and operations for many common tasks as well as content that integrates with several other ....

The following is an overview of what is included in the ready-made content:

+ **slang**
    + **base:** General purpose content.
        + **cmd:** Shell command content.
        + **files:** File management and manipulations, such as: read/write, copy/move/delete, and zip/unzip.
        + **mail:** Email related content. 
        + **network:** Network related actions, such as: pinging and performing REST calls. 
        + **remote_command_execution**
            + **ssh:** Run SSH commands.
        + **strings:** String actions and manipulations, such as: match, replace, occurrence counter. 
        + **utils:** Utility actions, such as: random number generator, sleep, uuid generator.         
    + **consul:** [Consul](https://consul.io/) has multiple components, but as a whole, it is a tool for discovering and configuring services in your infrastructure.
    Content for interacting with Consul, such as dealing with endpoints and the key/value store.
    + **coreos:** [CoreOS](https://coreos.com/) is a Linux distribution that has been rearchitected to provide features needed to run modern infrastructure stacks.
    Content for interacting with a CoreOS cluster.
    + **docker:** [Docker](https://www.docker.com/) is an open platform for developers and sysadmins to build, ship, and run distributed applications.
        + **cadvisor:** [cAdvisor](https://github.com/google/cadvisor) (Container Advisor) provides container users an understanding of the resource usage and performance characteristics of their running containers.
        Queries to cAdvisor to get usage information of Docker containers and to possibly act on the received response.
        + **containers:** In Docker terminology, a read-write layer, plus the information about its Parent Image and some additional information like its unique id, networking configuration, and resource limits is called a container. 
        Working with Docker containers, such as: start/stop/delete.
        + **images:** In Docker terminology, a read-only Layer is called an image.
        Working with and maintaining Docker images, such as: pulling, listing, and deleting images.
        + **linux:** Linux in Docker, such as: checking disk space and validating SSH access.
        + **maintenance:** Maintaining a clean Docker environment, such as: retrieving and acting upon the status of MySQL and Linux
    + **jenkins:** [Jenkins](http://jenkins-ci.org/) is an application that monitors executions of repeated jobs, such as building a software project or jobs run by cron.
    Working with Jenkins jobs, such as: enable/disable, copy and delete.
    + **marathon:** Marathon is cluster-wide init and control system for services in cgroups or Docker containers.
    Working with apps, such as: creating, deleting, updating and listing.
    + **openstack** [OpenStack](https://www.openstack.org/) is a cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter.
    Working with servers, such as: create, delete, authenticate and check.  
