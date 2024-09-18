 - Containerization -

The term itself refers to using containers in running a program/content management system.
Even though the two sound similar, there are differences between a container and a virtual machine, and there are also different situations
where one of the two would be more effective as opposed to the other.

 - What is a Container and how does it work? -

A container is an isolated entity that runs on top of an operating system's kernel and is separate from other containers, that contains applications and some OS APIs.
Unlike virtual machines (VMs), all containers on a single machine will share that machine's kernel, making them more portable than a VM.
Despite sharing a kernel, having the containers separate allows for more consistent and efficient use, 
since programs running in different containers will not affect one another. They are also more lightweight than a VM, since they do not contain their own kernel but instead run on that of the operating system (or VM, containers can run inside VMs).




Sources:
https://learn.microsoft.com/en-us/virtualization/windowscontainers/about/containers-vs-vm
https://www.geeksforgeeks.org/virtualization-vs-containerization/