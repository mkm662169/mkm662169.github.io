# VIRTUALIZATION Vs. CONTAINERISATION

# Definitions:

*Virtualization* refers to the process of creating a software-based, or virtual, representation of something, such as virtual applications, servers, storage and networks, in the form of virtual machines. A virtual machine is an emulated equivalent of a computer system that runs on top of another system.

*Containerization*, on the other hand, is a lightweight alternative to full machine virtualization that involves encapsulating an application on a container with its own operating system environment. There is no need to allocate resources to the host operating system beforehand. This provides many of the benefits of loading an application onto a virtual machine, as the application can be run on any suitable physical machine without any worries about dependencies.

# Differences:

•	Containerization only works on Linux applications. With virtualization, applications can run on Windows or any other operating system that support the hypervisor.
•	Containers provide a way to virtualize an OS so that multiple workloads can run on a single OS instance. With VMs, the hardware is being virtualized to run multiple OS instances.
•	Whereas containers sit on top of a physical server and shares the host OS kernel, virtual machines sit within the physical server and “hold” the host resources they require to run. Thus, while containers may only be megabytes in size and only require seconds to start up, virtual machines on the other hand may be gigabytes in size and may require minutes to start.
•	Due to containers sharing a common operating system, management and maintenance is significantly easier which in the case of virtual machines carries a lot more overhead. 

# Containerization Over Virtualization:

The benefit of only having to use one instance of a container that can run on several machines seems highly beneficial and far less cumbersome. Also, the “light” nature of containers greatly reduces overhead compared to the overhead of virtualization.

# Virtualization Over Containerization:

With virtualization, all OS resources and those of the host machine are available to the applications contained in the virtual machines. Also, security is less of a concern as there are better controls and tools in the world of virtualization. 

# Useful Links:

•	[Containers vs Virtual machines](https://blog.netapp.com/blogs/containers-vs-vms/)
•	[What is the difference between containerization (Docker) and virtualization (VMWare, VirtualBox, Xen)?](https://www.quora.com/What-is-the-difference-between-containerization-Docker-and-virtualization-VMWare-VirtualBox-Xen)
•	[Containerization vs Virtualization – An introduction to Docker](https://jaxenter.com/containerization-vs-virtualization-docker-introduction-120562.html)
•	[Containerization vs Virtualization | Everything you need to know](https://www.cloudmanagementinsider.com/containerization-vs-virtualization/)
