# Module 6
# 6.1 & 6.2
  An act to protect networks, online activities,data, and files from unauthorized access, spam, fraud, 
  or criminal use is essential. This involves ensuring the confidentiality, integrity, and availability of information.
## What are the risks to having poor cybersecurity?
    Various risks exist, ranging from severe threats like malware wiping your system or attackers altering files to less
    critical ones like unauthorized credit card use, and while no guarantees exist, taking precautions can reduce these risks.
# 6.03, 6.04 & 6.05
  Security and compliance in AWS entail a shared responsibility, with AWS managing the infrastructure's physical security and
  operational aspects, while customers are responsible for the guest operating system, application software, and AWS security 
  group firewall configuration; this division of responsibility is often referred to as Security "of" the Cloud versus Security "in" the Cloud.
## AWS responsibility “Security of the Cloud”
  AWS is responsible for safeguarding the entirety of the infrastructure supporting AWS Cloud services, encompassing physical security measures
  for data centers, hardware components like servers and storage devices, software infrastructure hosting operating systems, and network infrastructure
  with continuous monitoring and redundancy.
## AWS responsibility “Security of the Cloud”
  AWS customers are responsible for securing their data and applications in the cloud, including tasks like OS and application security, firewall 
  configurations, and access management, with the extent of responsibility varying based on the AWS service used. Additionally, both AWS and customers 
  share the responsibility for managing various IT controls, such as patching, configuration, awareness, and customer-specific controls related to 
  data storage, services used, and access management.
# 6.06
## What is Identity and Access Management?
  AWS Identity and Access Management (IAM) is a web service for securely controlling user access to AWS resources. It's best practice to avoid using 
  the root user and instead create an IAM user for everyday tasks. You can also generate additional access keys for added security and control using IAM.
## Authorization in IAM
  Authorization means granting specific permissions to users, services, or applications through JSON policies, following the principle of least privilege,
  and these settings apply globally across all AWS Regions.
# 6.07
  Shared access to your AWS account; Granular permissions; Secure access to AWS resources for applications that run on Amazon EC2; Multi-factor authentication (MFA);
  Identity information for assurance; PCI DSS Compliance; Integrated with many AWS services; Eventually Consistent; Free to use
# 6.08, 6.9, 6.10 & 6.11
## IAM User : 
    An AWS IAM user, whether a person or application, is a unique entity within an AWS account, with distinct credentials for making API calls,
  separate from the root user.
## IAM Group:
    An IAM group is a collection of IAM users for streamlined permission management, with key features like multiple user inclusion, no nesting of groups, and the 
    absence of a default group for all AWS account users, necessitating manual user addition to such a group.
## IAM Policy:
    An IAM policy is a document that sets permissions for AWS users, with identity-based policies for users, roles, or groups, 
    and resource-based policies for specific resources like S3 buckets.
## IAM Role:
    An IAM role in AWS is a temporary permission grant, similar to an IAM user, used for delegating access to resources to
    entities that wouldn't typically have access.
# 6.12
    Securing Accounts: AWS Organizations, AWS Key Management Service (KMS), Amazon Cognito, AWS Shield, 
# 6.13
    Data protection, including encryption, is vital to safeguard valuable data both during transmission and storage, making it indecipherable 
    without the appropriate secret key even if accessed by unauthorized individuals.
## Data at Rest
   you can protect static data by either letting Amazon handle server-side encryption or managing client-side encryption, 
   applicable to AWS services using AWS Key Management Service.
## Data in Transit
  Data in Transit, including network traffic, is secured with TLS/SSL encryption; AWS offers the AWS Certificate Manager for provisioning, 
  managing, and deploying SSL/TLS certificates, ensuring data security for AWS services and resources.
## Securing S3 Buckets & Objects
  Recent security breaches have exposed the danger of improperly configured S3 buckets, leading Amazon to default to private access and 
  advocate for the principle of least privilege.
# 6.14, 6.15 & 6.16
  DevSecOps, emphasizing individual security responsibility and collaboration between developers and security teams, prioritizes security
  in the development process, enabling faster development while ensuring proactive risk management.
  
  
   
  
  
  
