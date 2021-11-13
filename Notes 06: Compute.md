# 6.01 What is Cyber Security?

* Cybersecurity is the art of protecting networks, devices, and data from unauthorized access or criminal use and the practice of ensuring confidentiality, integrity, and availability of information.

## What are the risks to having poor cybersecurity?
* There are many risks, some more serious than others. Among these dangers are malware erasing your entire system, an attacker breaking into your system and altering files, an attacker using your computer to attack others, or an attacker stealing your credit card information and making unauthorized purchases. There is no guarantee that even with the best precautions some of these things won't happen to you, but there are steps you can take to minimize the chances.

## What can you do to improve your cybersecurity?

* Recognize risks
* **Hacker, attacker, or intruder** – These terms are applied to the people who seek to exploit weaknesses in software and computer systems for their own gain. Although their intentions are sometimes benign and motivated by curiosity, their actions are typically in violation of the intended use of the systems they are exploiting. The results can range from mere mischief (creating a virus with no intentionally negative impact) to malicious activity (stealing or altering information).
* **Malicious code** – Malicious code (also called malware) is unwanted files or programs that can cause harm to a computer or compromise data stored on a computer. Various classifications of malicious code include viruses, worms, and Trojan horses.
* Malicious code may have the following characteristics:
  * It might require you to actually do something before it infects your computer. This action could be opening an email attachment or going to a particular webpage.
  * Some forms of malware propagate without user intervention and typically start by exploiting a software vulnerability. Once the victim computer has been infected, the malware will attempt to find and infect other computers. This malware can also propagate via email, websites, or network-based software.
  * Some malware claims to be one thing, while in fact doing something different behind the scenes. For example, a program that claims it will speed up your computer may actually be sending confidential information to a remote intruder.
* **Vulnerabilities** – Vulnerabilities are flaws in software, firmware, or hardware that can be exploited by an attacker to perform unauthorized actions in a system. They can be caused by software programming errors. Attackers take advantage of these errors to infect computers with malware or perform other malicious activity.
* To minimize risks:
  * Keep software up to date.
  * Run up-to-date antivirus software.
  * Use strong passwords.
  * Implement multi-factor authentication (MFA).
  * Install a firewall.

# 6.02 Professor Messer: Confidentiality, Integrity, Availability, and Safety (Video)
# 6.03 Introduction to AWS Security
* Amazon Web Services (AWS) delivers a scalable cloud computing platform designed 
for high availability and dependability, providing the tools that enable you to run a wide 
range of applications. Helping to protect the confidentiality, integrity, and availability of 
your systems and data is of the utmost importance to AWS
* The AWS infrastructure has been architected to be one of the most flexible and secure 
cloud computing environments available today.
* This infrastructure is built and managed not only according to security best practices 
and standards, but also with the unique needs of the cloud in mind. AWS uses 
redundant and layered controls, continuous validation and testing, and a substantial 
amount of automation to ensure that the underlying infrastructure is monitored and 
protected 24x7. AWS ensures that these controls are replicated in every new data 
center or service

# 6.04 AWS Shared Responsibility Model
* Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates. 

## AWS responsibility “Security of the Cloud”
* Physical security of data centers with controlled, need-based access; located in nondescript facilities, with 24/7 security guards; two-factor authentication; access logging and review; video surveillance; and disk degaussing and destruction.
* Hardware infrastructure, such as servers, storage devices, and other appliances that AWS relies on.
* Software infrastructure, which hosts operating systems, service applications, and virtualization software.
* Network infrastructure, such as routers, switches, load balancers, firewalls, and cabling. AWS also continuously monitors the network at external boundaries, secures access points, and provides redundant infrastructure with intrusion detection.

## Customer responsibility “Security in the Cloud”
* While the cloud infrastructure is secured and maintained by AWS, customers are responsible for security of everything they put in the cloud.
* The customer is responsible for what is implemented by using AWS services and for the applications that are connected to AWS. The security steps that you must take depend on the services that you use and the complexity of your system. Customer responsibilities include selecting and securing any instance operating systems, securing the applications that are launched on AWS resources, security group configurations, firewall configurations, network configurations, and secure account management
* Inherited Controls – Controls which a customer fully inherits from AWS.
* Physical and Environmental controls
Shared Controls – Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services. Examples include:
* Patch Management – AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.
* Configuration Management – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.
* Awareness & Training - AWS trains AWS employees, but a customer must train their own employees.
Customer Specific – Controls which are solely the responsibility of the customer based on the application they are deploying within AWS services.

# 6.05 AWS Security Best Practices
* Information security is of paramount importance to Amazon Web Services (AWS) 
customers. Security is a core functional requirement that protects mission- critical 
information from accidental or deliberate theft, leakage, integrity compromise, and 
deletion. 
* Information security is of paramount importance to Amazon Web Services (AWS) 
customers. Security is a core functional requirement that protects mission- critical 
information from accidental or deliberate theft, leakage, integrity compromise, and 
deletion. 

# 6.06 Introduction to IAM
## What is Identity and Access Management?
* AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources for your users. You use IAM to control who can use your AWS resources (authentication) and what resources they can use and in what ways (authorization).

## Authorization in IAM
* Authorization is the process of determining what permissions a user, service or application should be granted. After a user has been authenticated, they must be authorized to access AWS services.
* By default, IAM users do not have permissions to access any resources or data in an AWS account. Instead, you must explicitly grant permissions to a user, group, or role by creating a policy, which is a document in JavaScript Object Notation (JSON) format. A policy lists permissions that allow or deny access to resources in the AWS account.
* To assign permission to a user, group or role, you must create an IAM policy
* The principle of least privilege is an important concept in computer security. It promotes that you grant only the minimal user privileges needed to the user, based on the needs of your users. When you create IAM policies, it is a best practice to follow this security advice of granting least privilege. 
* Note that the scope of the IAM service configurations is global. The settings are not defined at an AWS Region level. IAM settings apply across all AWS Regions.

# 6.07 Features of IAM
* Shared access to your AWS account: You can grant other people permission to administer and use resources in your AWS account without having to share your password or access key.
* Granular permissions
* Secure access to AWS resources for applications that run on Amazon EC2
* Multi-factor authentication (MFA)
* Identity federation
* Identity information for assurance
* PCI DSS Compliance
* Integrated with many AWS services
* Eventually Consistent
* Free to use

# 6.08 Essential Elements of IAM

* An IAM user is a person or application that is defined in an AWS account, and that must make API calls to AWS products. Each user must have a unique name (with no spaces in the name) within the AWS account, and a set of security credentials that is not shared with other users.
* Programmatic access via the AWS Command Line Interface (CLI) or AWS Software Development Kit (SDK)
* AWS Management Console access via IAM were a 12 digit Account ID, IAM Username, and IAM Password are assigned with optional multi-factor authentication (MFA).

## IAM Group
* A group can contain many users, and a user can belong to multiple groups.
* Groups cannot be nested. A group can contain only users, and a group cannot contain other groups.
* There is no default group that automatically includes all users in the AWS account. If you want to have a group with all account users in it, you need to create the group and add each new user to it.
* An IAM policy is a document that defines permissions to determine what users can do in the AWS account. A policy typically grants access to specific resources and specifies what the user can do with those resources. Policies can also explicitly deny access.
* There are two types of policies, identity-based policies and resource-based policies. Identity-based policies are permissions policies that you can attach to a principal (or identity) such as an IAM user, role, or group. These policies control what actions that identity can perform, on which resources, and under what conditions. Resource-based policies are JSON policy documents that you attach to a resource, such as an S3 bucket. These policies control what actions a specified principal can perform on that resource, and under what conditions.
* An IAM role is a tool for granting temporary access to specific AWS resources in an AWS account.

## 6.09 Four Ways to use IAM
* AWS management console is a browser-based interface to manage IAM and AWS resources
