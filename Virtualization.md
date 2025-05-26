# Virtualization

- Here we try to create a virtual version of something
    1. Server
    2. Storage
    3. Device
    4. Operating System
    5. Network
    6. Application

- Ultimate goal is to use software to simulate hardware functionality and create multipel systems from a single physical machine

# Key Components of Virtualization

![Virtualization](https://raw.githubusercontent.com/Digu-patil/RefrenceDiagrams/main/CS-Virtualization.svg)   

1. Host OS - This is the OS running on the physical machine (only for Type 2 Hosted hypervisors)
2. Guest OS - OS running inside a VM
3. Virtual Machine (VM) - Its a virtual computer that behaves like a real one, with virtual resources
4. Hypervisor - This is the software that creates and manages VMs
    - Type 1 (Bare Metal) = Runs directly on the hardware/server (VMware ESXi)
    - Type 2 (Hosted) = Runs on a host OS (VirtualBox, VMware Workstation)

![Hypervisor Types](https://raw.githubusercontent.com/Digu-patil/RefrenceDiagrams/main/CS-Type-of-Hypervisors.svg)   

# Types of Virtualization

1. Hardware Virtualization 
    - Virtual Machines are created using hypervisors, these would be bare metal.
    - Amazon EC2, Azure Virtual Machines (Hyper-V)
2. OS Virtualization 
    - Same OS Kernel is shared by applications
    - Everything is isolated, but host OS Kernel is shared.
3. Storage Virtualization
    - S3, EBS
4. Network Virtualization
    - Logical network components are provided here
    - AWS Route 53, Elastic Load Balancer
5. Desktop Virtualization
    - Hosted remote desktops
    - Amazon Workspaces
6. Application Virtulaization
    - Application are run in an isolated environments separate from the underlying OS
    - The App is run on an virtualized environment that sits on top of the OS.
    - AWS Lambda, Azure Function

Refer the below image to under the evolution of computing and to understand virtualization

![Evolution of Computing](https://raw.githubusercontent.com/Digu-patil/RefrenceDiagrams/main/CS-Computing&Virtualization.svg)   
