# DevOps guide

mermaid
graph TD
A[DevOps] --> B[Linux]
A --> C[Tooling]
A --> D[Networking]
A --> E[Kubernetes]
A --> F[Filesystems]
C --> G[Source control management (e.g., Git, SVN)]
C --> H[Build tools (e.g., Maven, Gradle)]
C --> I[Testing tools (e.g., JUnit, TestNG)]
C --> J[Containerization tools (e.g., Docker, Podman)]
C --> K[Container orchestration tools (e.g., Kubernetes, Docker Swarm)]
C --> L[Configuration management tools (e.g., Ansible, Chef, Puppet)]
C --> M[Infrastructure as Code tools (e.g., Terraform, CloudFormation)]
D --> N[Network protocols (e.g., TCP/IP, HTTP, HTTPS)]
D --> O[IP addressing and subnetting]
D --> P[DNS (Domain Name System)]
D --> Q[Load balancing]
D --> R[Network security (e.g., firewalls, VPNs)]
E --> S[Kubernetes architecture and components]
E --> T[Deploying and managing applications on Kubernetes]
E --> U[Kubernetes resources (e.g., pods, services, deployments)]
E --> V[Kubernetes operators and controllers]
F --> W[Different types of file systems (e.g., ext4, XFS, NTFS)]
F --> X[File permissions and ownership]
F --> Y[Filesystem security]

