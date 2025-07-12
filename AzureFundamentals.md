
## Azure Fundamentals

### Cloud Computing

Delivery of computing services over the internet (enabling faster innovation, flexible resources, and economies of scale).

* **Compute** – Where all operations take place
* **Networking** – Responsible for flow of information and communication
* **Storage** – Repository for storing and retaining data and information
* These resources are hosted in a datacenter

#### Advantages:

* Financial advantages
* Reduced maintenance overhead

---

### Cloud Models

#### 1. Private Cloud

* Single organization has complete control over infrastructure
* High overhead and technical expertise needed
* Full control of access and management

#### 2. Public Cloud

* Built and managed by third-party provider
* Open to all users
* Pay-as-you-go
* Minimal maintenance burden

#### 3. Hybrid Cloud

* Combines public + private cloud
* Flexibility and regulatory compliance

#### 4. Multi-cloud

* Uses multiple public cloud providers
* Enhances redundancy and flexibility

#### 5. Azure Arc

* Manages resources across Azure, on-prem, hybrid, or multi-cloud environments

#### 6. Azure VMware Solution

* Run VMware workloads in Azure
* Useful for migration from private to public cloud

---

### CapEx vs OpEx

| CapEx                            | OpEx                              |
| -------------------------------- | --------------------------------- |
| One-time upfront expense         | Ongoing expense                   |
| Examples: buildings, datacenters | Examples: cloud services, leasing |
| Physical assets                  | Pay-as-you-go resources           |

---

### Cloud Benefits

1. **High Availability** – Maximum uptime
2. **Scalability** – Adjust resources based on demand (Vertical and Horizontal)
3. **Reliability** – Recover from failures, decentralized infrastructure
4. **Predictability** – Forecast cost and performance using Azure tools
5. **Security** – Encryption, IAM, SWAT, compliance
6. **Governance** – Enforces policies and compliance
7. **Manageability** – CLI, API, portal, PowerShell management options

---

### Shared Responsibility Model

| Cloud Provider                         | Consumer                          |
| -------------------------------------- | --------------------------------- |
| Physical datacenter, networking, hosts | Data, access, devices, identities |

Responsibility varies by service model (IaaS, PaaS, SaaS)

---

### Cloud Service Models

#### Infrastructure as a Service (IaaS)

* Full control
* Provider manages hardware
* You manage OS, apps, network

#### Platform as a Service (PaaS)

* Provider manages OS, DB, middleware
* You focus on app logic and data

#### Software as a Service (SaaS)

* Provider manages everything
* User manages access and data only

---

### Azure Architecture

#### Regions

* Made of multiple datacenters
* Data residency, low latency

#### Availability Zones

* Physically separate datacenters in a region
* Protects against datacenter failure

#### Region Pairs

* At least 300 miles apart
* Automatic replication, prioritized recovery

#### Sovereign Regions

* For government agencies (e.g., Azure Government, China 21Vianet)

---

### Azure Management

#### Resource

* Anything deployed in Azure (VM, DB, etc.)

#### Resource Group

* Logical container for resources
* Scoped actions (e.g., RBAC, deletion)

#### Subscription

* Billing and access control boundary
* Can separate environments or org units

#### Management Groups

* Group multiple subscriptions
* Apply policies, RBAC at a higher level

---

### Azure Compute Services

#### Virtual Machines (VMs)

* Full OS control, customizable
* IaaS

#### Scale Sets

* Manage VMs in a group
* Auto scale with demand

#### Availability Sets

* Protect from simultaneous failures
* Uses fault and update domains

#### Azure Virtual Desktop

* Desktop and app virtualization
* Multi-session Windows 10/11

#### Azure Containers

* Lightweight app hosting
* Examples: Docker, Kubernetes (AKS)

#### Azure Functions

* Serverless compute
* Trigger-based execution

---

### Application Hosting Options

* **VMs** – Full control
* **Containers** – Lightweight, portable
* **App Service** – PaaS for web apps, APIs, mobile backends

  * Supports .NET, Java, Node.js, PHP, Python

---

### Azure Networking

#### Virtual Network (VNet)

* Isolated network environment
* Connects Azure resources

#### Subnets

* Segment a VNet into logical parts

#### Communication

* Between Azure resources
* Between Azure and on-prem via VPN or ExpressRoute

#### VPN Gateway

* Secure encrypted tunnels
* Types: Point-to-site, Site-to-site, VNet-to-VNet

#### ExpressRoute

* Private, high-speed connection
* Not over public internet

---

### Azure DNS

* Provides name resolution
* Supports public and private DNS
* Integrated with Azure RBAC and Activity logs

---

### Azure Storage

#### Storage Account

* Namespace for Azure Storage data

#### Redundancy Options

* **LRS** – Single datacenter
* **ZRS** – Across 3 zones
* **GRS** – Primary + secondary region
* **GZRS** – Zones + Geo-redundant
* **RA-GRS / RA-GZRS** – Read access enabled

#### Storage Services

* **Blob Storage** – Unstructured data
* **File Storage** – SMB/NFS
* **Queue Storage** – Messaging
* **Disk Storage** – VM disks
* **Table Storage** – NoSQL data

---

### Azure Data Migration

#### Azure Migrate

* Assess and migrate on-prem workloads

#### Azure Data Box

* Offline transfer via physical device

#### File Movement Tools

* **AzCopy** – CLI for blob/file transfer
* **Storage Explorer** – GUI for storage
* **File Sync** – Hybrid sync service

---

### Azure Directory Services

#### Microsoft Entra ID

* Cloud-based identity and access management
* Formerly Azure AD

#### Microsoft Entra Domain Services

* Domain join, Group Policy, LDAP
* AD in the cloud without managing DCs

---

### Azure Authentication

#### Single Sign-On (SSO)

* One credential, multiple resources

#### Multifactor Authentication (MFA)

* Two or more authentication methods

  * Something you **know** (password)
  * Something you **have** (OTP)
  * Something you **are** (biometrics)

#### Passwordless Authentication

* High security and convenience

---
