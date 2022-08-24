# **Docker Learning**

### *Docker is nothing but a platform for running,building and shipping containers.*

- Before diving into docker it is very important to be crystal clear about the difference between two things that is *`virtual machine`* and *`container`*.

- **Virtual Machine**:Virtual machine is just an abstration of physical hardware. We can run several isolated virtual machnes on a single physical machine. Suppose if you have a macbook machine you can run both Windows & Linux on top of it using a tool called hypervisor which is a software to create and  manage virtual machines. Some of commonly used hypervisors are Virtual Box and VMware.

- **Container**:A container is a nothing just an operating system virtualization.It provides us an isolated environment for running applications on a single operating system.A docker container technically an OS process having its own file system provided by docker image and all containers share kernel of host OS.

- **Image**:A Docker image is a file used to execute code in a Docker container.It consists of cut-dow OS,dependencies,environment variables,third party libraries and everything an application requires to run.

- **Workflow of Docker**: Before the advent of docker,there often arised situations where an application runs on a developer's machine but fails to run on production machine due to reasons like version mismatch,different configuration settings etc.However after advent of docker you can package all essential components required by an apllication into an image and push it on dockerhub and then you can pull on it you production machine and run it inside docker containers.


- **Dockerfile**:All instructions for building an image is written into Dockerfile.

  
## Why prefer containers over VM's?

- VM is resource intesnsive as it has its own OS and takes a slice of hardware where as containers are lightweight because they are just special types of processes.
- Time taken to start a container is much less than time taken to start a VM.

### Fun Facts

- We can't run Windows 10 container on a linux machine but we can run a linux container on a Windows 10 machine.
- MacOS don't have inbuilt support for containers so docker uses a lightweight linux VM to run linux containers.

