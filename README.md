# Docker
### What is Docker?
Docker is a containerisation platform, open source platform, that enables developers to separate their applications from their infrastructure. It does this by utilising containers.
Containers images are lightweight, standalone, executable packages of software that include everything needed to run an application: code, runtime, system tools, system libraries and settings.
It  is a tool created by Google and later made open source and transferred to the Linux foundation. It helps create, modify, delete and otherwise manage containers

### Containers and VMs
A container is similar to a Virtual Machine in that both are closed boxes (separated from the host machine) on which to run software. The main difference between a VM and a container is that while a virtual machine simulates the whole operating system on which to run software, a container is only provided with the minimal necessary dependencies to run a specific application, and is therefore much more lightweight and faster, but while trading-off flexibility and scope.
Virtualization enables you to run multiple operating systems on the hardware of a single physical server, while containerization enables you to deploy multiple applications using the same operating system on a single virtual machine or server.
### Benefits of using containers
- Docker is more lightweight
- Start-up time is much faster
- Easily adaptable
- Run multiple containers as they share the same OS
- Integrate with other tools
- They don't require the whole OS

### Who is using Docker?
- Major companies such as Business Insider, Spotify, Yelp, ADP, eBay, Expedia, Groupon, ING
- Over 50% of companies are using Docker in 2021

### What is Micro-Services architecture
Microservices are small apps that are meant to do one thing with as little information as possible.
They should perform only one task and stopping them should not affect any of the other apps.

The idea behind Micro-Services Architecture is to split your application into smaller inter-connected services. This allows them to be:
- Highly maintainable and testable
- Loosely coupled
- Independently deployable
- Organised around business capabilities

### Benefits of Micro-Services architecture
Implementing this correctly can result in the following benefits:
- Code can be updated faster and more efficiently
- Use different stacks and programming languages for different components
- Components can be scaled independently of one another which reducing cost
- Service usability
- Service autonomy
- Improved Scalability
- Better security and compliance
- Faster release of product to customers

### Monolithic vs Micro-Services
- Monolithic Architecture is tightly-coupled architecture where each component and its associated components must be present in order for code to be executed or compiled
- Monolithic is preferred if you don't have a large team to handle all of your tasks
- Micro-Services is a complex solution for complex problems. If you aren't facing complex problems, it can become difficult to handle.