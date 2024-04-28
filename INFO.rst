Open Web Application Security Project
=====================================

Virtual Network
---------------
| Virtual Network

Challenges of impementing Security
----------------------------------
• Focus on fast development and new features. (incentivize)
• Provides business value.
• Bring customer, Direct value for users
• Bring money, staying ahead of competitors
• No rewars for implementing great security (Goalkeeper)
• Developers implementing new featurs (Goal scorer)
• Security is an afterthought.
• Application systems become more complex
• Microservices
• Containers
• Kubernetes
• Cloud
• Multiple Databases
• Caching
• No SQL
• Primary
• SQL
• Memory
• API
• Many Entrypoints
• Large Attack Surface

Vulnerabilities of each layer
• Application
• Own source code
• Third party code
• Threats/Attacks
• SQL Injection
• Cross-Site Scripting
• Client or Server Request Forgery
• Container Runtime
• Image Layers
• OS base image
• Docker image consist of your application code, but also underlying operating systems, runtime, tools and package dependencies.
• Kubernetes
• Cluster secured? from outside
• API server public accessible
• Unneeded ports open
• Access Management to cluster
• Static long-term credentials or short-lived tokens?
• Security within the cluster?
• Pod communication restricted
• Access to Control Plane processes?
• Pod to Pod encryption
• Cloud Infrastructure (running in cloud?)
• SSH into Worker Nodes directly?
• Is VPC wide open?
• Permissions not strict enough
• Credentials spread around the whole company
• Static credentials on engineer' computer
• CI/CD pipeline
• CI/CD is like an orchestrator, having access to many other systems.
• Does your CI/CD tool has too many permissions.
• Will attacker get access to all credentials?
• What permission do these credentials have?
