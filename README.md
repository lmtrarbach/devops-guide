# DevOps Guide

This mind map shows the key topics that a person interested in learning DevOps should focus on. The mind map is divided into several main areas, each with its own subtopics.

## Mind Map

```mermaid
graph TD
A[DevOps] --> B[Linux]
A --> C[Tooling]
B --> D[Networking]
B --> E[Kubernetes]
B --> F[Filesystems]
C --> G[Source Control]
C --> H[Build Tools]
C --> I[Testing Tools]
C --> J[Containerization]
C --> K[Orchestration]
C --> L[Configuration Mgmt.]
C --> M[Infrastructure as Code]
D --> N[Network Protocols]
D --> O[IP Addressing]
D --> P[DNS]
D --> Q[Load Balancing]
D --> R[Network Security]
E --> S[K8s Architecture]
E --> T[K8s Deployment]
E --> U[K8s Resources]
E --> V[K8s Operators]
F --> W[File System Types]
F --> X[File Permissions]
F --> Y[Filesystem Security]
G --> GA[Git]
G --> GB[SVN]
J --> JA[Docker]
J --> JB[Podman]
K --> KA[Kubernetes]
K --> KB[Docker Swarm]
L --> LA[Ansible]
L --> LB[Chef]
L --> LC[Puppet]
M --> MA[Terraform]
M --> MB[CloudFormation]
A[DevOps] --> H[Culture]
H --> HL[3 Ways]
H --> HM[CALMS]
H --> HL[Team Topologies]
H --> HN[SRE]
H --> HM[Agile]
HM --> HO[LEAN]
HM --> HP[Scrum]
A[DevOps] --> N[Software Engineering]
N --> NA[APIs]
N --> NB[Programming]
N --> NC[Scripting]
N --> ND[Databases]
N --> NE[Solutions Design]
N --> NF[UML]




```


## Topics

### Linux

- [Linux Operating System](https://github.com/lmtrarbach/devops-guide/wiki/Introduction-to-the-Linux-Operating-System)
- [Basic Linux Commands](https://github.com/lmtrarbach/devops-guide/wiki/Basic-Linux-Commands)
- [Advanced Linux Commands](https://github.com/lmtrarbach/devops-guide/wiki/Advanced-Linux-Commands)
- [Linux Networking Configuration](https://github.com/lmtrarbach/devops-guide/wiki/Basic-Network-Configuration)
- [Linux Networking Commands](https://github.com/lmtrarbach/devops-guide/wiki/Linux-Networking-Commands)
- [Linux Filesystem](https://github.com/lmtrarbach/devops-guide/wiki/Filesystem-Hierarchy-Standard)
- [Linux Services and Kernel](https://github.com/lmtrarbach/devops-guide/wiki/Linux-Services)
- [Linux bridges and interfaces](https://github.com/lmtrarbach/devops-guide/wiki/Linux-Bridges-and-Interfaces)
- [The-Linux-Programming-Interface](https://github.com/lmtrarbach/devops-guide/wiki/The-Linux-Programming-Interface)


### Tooling

- Source control management (e.g., Git, SVN)

- Containerization tools (e.g., Docker, Podman)

- Container orchestration tools (e.g., Kubernetes, Docker Swarm)

- Configuration management tools (e.g., Ansible, Chef, Puppet)

- Infrastructure as Code tools (e.g., Terraform, CloudFormation)

### Networking

- Network protocols (e.g., TCP/IP, HTTP, HTTPS)

- IP addressing and subnetting

- DNS (Domain Name System)

- Load balancing

- Network security (e.g., firewalls, VPNs)

### Kubernetes

- Kubernetes architecture and components

- Deploying and managing applications on Kubernetes

- Kubernetes resources (e.g., pods, services, deployments)

- Kubernetes operators and controllers

### Filesystems

- Different types of file systems (e.g., ext4, XFS, NTFS)

- File permissions and ownership

- Filesystem security

## Getting Started

To get started with DevOps, you should focus on learning the basics of Linux and Lean culture, as well as mastering the key tools and technologies used in the field. The mind map above provides a useful overview of the different areas to focus on, and the subtopics that fall under each area.

Once you've mastered the basics, you can start exploring more advanced topics like cloud native development, advanced Kubernetes features, and more. Good luck on your DevOps journey!
