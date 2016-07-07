#Docker in Action
By by Jeff Nickoloff


> Docker is a tool that helps solve common problems like installing, removing, upgrading, distributing, trusting, and managing software.

#### Part 1 - Keeping a Tidy Computer
 
 - Programs running inside Docker containers interface directly with the host’s Linux kernel. Because there’s no additional layer between the program running inside the container and the computer’s operating system, no resources are wasted by running redundant software or simulating virtual hardware.
 
 - Problems that Docker can solve 
    - What happens if one application needs an upgraded dependency but the other does not?
    - What happens when you remove an application? Is it really gone?
    - Can you remove old dependencies?
    - Can you remember all the changes you had to make to install the software you now want to remove?

 - At present, Docker runs natively on Linux and comes with a single virtual machine for OS X and Windows environments. This convergence on Linux means that software running in Docker containers need only be written once against a consistent set of dependencies.
    - On OS X and Windows, Docker uses a single, small virtual machine to run all the containers. By taking this approach, the overhead of running a virtual machine is fixed while the number of containers can scale up.
