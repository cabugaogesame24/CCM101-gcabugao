# Cloud Provider Core Infrastructure Comparison

| Infrastructure Component | Amazon Web Services (AWS) | Microsoft Azure | Google Cloud Platform (GCP) |
|---|---|---|---|
| *Compute* | Amazon EC2 (Elastic Compute Cloud) | Azure Virtual Machines | Google Compute Engine (GCE) |
| *Storage* | Amazon S3 (Object), EBS (Block), EFS (File) | Blob Storage, Managed Disks, Azure Files | Cloud Storage, Persistent Disk, Filestore |
| *Networking* | VPC, EC2 Elastic IP, ALB, Route 53 | Virtual Network, Public IP, Load Balancer, Azure DNS | VPC, External IP, Cloud Load Balancing, Cloud DNS |
| *Identity & Access Management (IAM)* | AWS IAM | Azure AD / Microsoft Entra ID | Cloud IAM |

---

## Guide Questions

### 1. Which cloud provider offers the broadest range of services?
*AWS* generally offers the broadest range of services. It was the first major public cloud and has expanded into over 200+ fully featured services across computing, storage, databases, analytics, AI, IoT, and enterprise applications, making it the most mature and widely supported ecosystem.

### 2. Which platform would you recommend for an organization that primarily uses Microsoft products? Why?
*Microsoft Azure* is the best choice. It integrates natively with Microsoft 365, Windows Server, Active Directory, SQL Server, and .NET, offering seamless single sign-on, unified licensing, and familiar management portals that reduce operational overhead.

### 3. Which platform is widely recognized for AI, Machine Learning, and Kubernetes services?
*Google Cloud Platform (GCP)* is widely recognized in these areas. It developed Kubernetes and offers industry-leading AI/ML tools built on the same technologies that power Google Search, YouTube, and DeepMind — giving it native advantages in container orchestration and advanced analytics.

### 4. What similarities did you observe among the three cloud providers?
All three offer nearly identical core infrastructure categories — virtual machines, scalable storage, isolated virtual networks, and role-based access control — using similar pay-as-you-go pricing models. They all deliver Infrastructure-as-Code support, global regional availability, and consistent service concepts even under different product names.
