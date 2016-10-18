# Cloud Computing
Cloud Computing refers to manipulating, configuring, and accessing the hardware and software resources remotely. It offers online data storage, infrastructure, and application.

Cloud computing offers platform independency, as the software is not required to be installed locally on the PC. Hence, the Cloud Computing is making our business applications mobile and collaborative.

![crm](https://cloud.githubusercontent.com/assets/22348863/19489250/1b0c88f4-9588-11e6-87ac-e8f06b7466e6.jpg)

# Deployment Models
- PUBLIC CLOUD: The public cloud allows systems and services to be easily accessible to the general public. Public cloud may be less secure because of its openness.
- PRIVATE CLOUD: The private cloud allows systems and services to be accessible within an organization. It is more secured because of its private nature.
- COMMUNITY CLOUD: The community cloud allows systems and services to be accessible by a group of organizations.
- HYBRID CLOUD: The hybrid cloud is a mixture of public and private cloud, in which the critical activities are performed using private cloud while the non-critical activities are performed using public cloud.

# Service Models
- INFRASTRUCTURE-AS-A-SERVICE (IAAS): IaaS provides access to fundamental resources such as physical machines, virtual machines, virtual storage, etc.
- PLATFORM-AS-A-SERVICE (PAAS): PaaS provides the runtime environment for applications, development and deployment tools, etc.
- SOFTWARE-AS-A-SERVICE (SAAS): SaaS model allows to use software applications as a service to end-users.

# Risks related to Cloud Computing
- Security and Privacy: It is the biggest concern about cloud computing. Since data management and infrastructure management in cloud is provided by third-party, it is always a risk to handover the sensitive information to cloud service providers. Although the cloud computing vendors ensure highly secured password protected accounts, any sign of security breach may result in loss of customers and businesses.

- Lock In: It is very difficult for the customers to switch from one Cloud Service Provider (CSP) to another. It results in dependency on a particular CSP for service.

- Isolation Failure: This risk involves the failure of isolation mechanism that separates storage, memory, and routing between the different tenants.

- Management Interface Compromise: In case of public cloud provider, the customer management interfaces are accessible through the Internet.

- Insecure or Incomplete Data Deletion: It is possible that the data requested for deletion may not get deleted. It happens because either of the following reasons- Extra copies of data are stored but are not available at the time of deletion, Disk that stores data of multiple tenants is destroyed.

# Technologies
There are certain technologies working behind the cloud computing platforms making cloud computing flexible, reliable, and usable.
- Virtualization: is a technique, which allows to share single physical instance of an application or resource among multiple organizations or tenants (customers).
    1. Full Virtulization:in which a complete installation of a machine is run on another.
    2. Paravirtulaization:allows multiple operating systems run on a single hardware device at same time.
- Service-Oriented Architecture (SOA): Service-Oriented Architecture helps to use applications as a service for other applications regardless the type of vendor, product or technology. Therefore, it is possible to exchange the data between applications of different vendors without additional programming or making changes to services.
- Grid Computing: refers to distributed computing, in which a group of computers from multiple locations are connected with each other to achieve a common objective.
- Utility computing: is based on Pay-per-Use model. It offers computational resources on demand as a metered service. Cloud computing, grid computing, and managed IT services are based on the concept of utility computing.

# Cloud Components
![cs model](https://cloud.githubusercontent.com/assets/22348863/19496658/10d68362-95a6-11e6-870f-836c1f4d87c1.gif)

It has three components
- Client computers: Clients are the device that the end user interact with cloud. Three types of clients: 1.) Mobile 2.) Thick 3.) Thin (Most Popular)
- Distributed Servers: Often servers are in geographically different places, but server acts as if they are working next to each other. 
- Datacenters: It is collection of servers where application is placed and is accessed via internet.

Central Server: It Administers the system such as monitoring traffic, client demands to ensure everything runs smoothly. It uses a special type of software called Middleware. Middleware allow computer to communicate each other.

Iterative server- They are severely limited in their performance because only one client at a time can be handled.

Concurrent server- The main server method launches a thread to handle each client request, so multiple clients can simultaneously interact with the server while the server continues to listen for additional clients.
