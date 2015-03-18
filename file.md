#Content

The **slang-content** repository contains ready-made Slang flows and operations for many common tasks as well as content that integrates with several other systems.

The following is an overview of what is included in the ready-made content:

+ **slang**
  + **base:** This folder contains general purpose content.
    + **cmd:** Shell command content.
    + **files:** File management and manipulations, such as: read/write, copy/move/delete, and zip/unzip.
    + **mail:** Email related content. 
    + **network:** Network related actions, such as: pinging and performing REST calls. 
    + **remote_command_execution**
      + **ssh:** SSH command related content.
    + **strings:** String actions and manipulations, such as: match, replace, occurrence counter. 
    + **utils:** Utility actions, such as: random number generator, sleep, uuid generator.         
  + **consul:** [Consul](https://consul.io/) has multiple components, but as a whole, it is a tool for discovering and configuring services in your infrastructure. This folder contains content for interacting with Consul, such as dealing with endpoints and the key/value store.
  + **coreos:** [CoreOS](https://coreos.com/) is a Linux distribution that has been rearchitected to provide features needed to run modern infrastructure stacks. This folder contains content for interacting with a CoreOS cluster.
  + **docker:** [Docker](https://www.docker.com/) is an open platform for developers and sysadmins to build, ship, and run distributed applications.
    + **cadvisor:** [cAdvisor](https://github.com/google/cadvisor) provides container users an understanding of the resource usage and performance characteristics of their running containers. This folder contains content for querying cAdvisor to get usage information of Docker containers and to possibly act on the received responses.
    + **containers:** In Docker terminology, a container is a read-write layer, plus the information about its Parent Image and some additional information like its unique id, networking configuration, and resource limits. This folder contains content for working with Docker containers, such as: start, stop and delete.
    + **images:** In Docker terminology, an image is a read-only layer. This folder contains content for working with and maintaining Docker images, such as: pulling, listing, and deleting images.
    + **linux:** This folder contains content for working with Linux in Docker, such as: checking disk space and validating SSH access.
    + **maintenance:** This folder contains content for maintaining a clean Docker environment, such as: retrieving and acting upon the status of MySQL and Linux checks.
  + **jenkins:** [Jenkins](http://jenkins-ci.org/) is an application that monitors executions of repeated jobs, such as building a software project or jobs run by cron. This folder contains content for working with Jenkins jobs, such as: enable,  disable, copy and delete.
  + **marathon:** [Marathon](https://mesosphere.github.io/marathon/) is cluster-wide init and control system for services in cgroups or Docker containers. This folder contains content for working with apps, such as: creating, deleting, updating and listing.
  + **openstack:** [OpenStack](https://www.openstack.org/) is a cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter.This folder contains content for working with servers, such as: create, delete, authenticate and check.  
