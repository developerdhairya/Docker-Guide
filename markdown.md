# **Docker Learning**

## *Docker is nothing but a platform for running,building and shipping containers.*

---

- Before diving into docker it is very important to be crystal clear about the difference between two things that is *virtual machine* and *container*.

- **Virtual Machine**:Virtual machine is nothing an abstration of physical hardware. We can run several virtual machnes on a single physical machine. Suppose if you have a macbook machine you can run both Windows & Linux on top of it using a tool called hypervisor which is a software to create and  manage virtual machines.Some of commonly used hypervisors are Virtual Box and VMware.

- **Container**:A container is a nothing just an operating system virtualization.It is standalone unit of software that packages up code and all dependencies an application will require to run.It provides us an isolated environment for running applications on a single operating system.

- A docker container technically an OS process having its own file system.

- Before the advent of docker,there often arised situations where an application runs on a developer's machine but fails to run on production machine.
