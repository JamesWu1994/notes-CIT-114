# 2.1 A Brief History
* The idea of cloud traces back to the origins of utility computing, a concept that computer scientist John McCarthy publicly proposed in 1961
  * "If computers of the kind I have advocated become the computers of the future, then computing may someday be organized as a public utility just as the telephone system is a public utility... The computer utility could become the basis of a new and important industry."
* The general public has been leveraging forms of Internet-based computer utilities since the mid-1990s
* Search engines (Yahoo!, Google), e-mail services (Hotmail, Gmail), open publishing platforms (MySpace, Facebook, YouTube), and other types of social media (Twitter, LinkedIn). Though consumer-centric, these services popularized and validated core concepts that form the basis of modern-day cloud computing.
* In the late 1990s, Salesforce.com pioneered the notion of bringing remotely provisioned services into the enterprise.
* In 2002, Amazon.com launched the Amazon Web Services (AWS) platform, a suite of enterprise-oriented services that provide remotely provisioned storage, computing resources, and business functionality.
* A slightly different evocation of the term "Network Cloud" or "Cloud" was introduced in the early 1990s throughout the networking industry.
* It wasn't until 2006 that the term "cloud computing" emerged in the commercial arena.
# 2.2 Business Drivers
* The origins and inspirations of many of the characteristics, models, and mechanisms covered throughout subsequent chapters can be traced back to the upcoming business drivers.
## Capacity Planning
* Capacity planning is the process of determining and fulfilling future demands of an organization's IT resources, products, and services.
* Within this context, capacity represents the maximum amount of work that an IT resource is capable of delivering in a given period of time.
* A discrepancy between the capacity of an IT resource and its demand can result in a system becoming either inefficient (over-provisioning) or unable to fulfill user needs (under-provisioning).
* Seeks to minimize this discrepancy
* Different capacity planning strategies exist:
  * Lead Strategy - adding capacity to an IT resource in anticipation of demand
  * Lag Strategy - adding capacity when the IT resource reaches its full capacity
  * Match Strategy - adding IT resource capacity in small increments, as demand increases
* Planning for capacity can be challenging because it requires estimating usage load fluctuations.
* There is a constant need to balance peak usage requirements without unnecessary over-expenditure on infrastructure.
## Cost Reduction
* A direct alignment between IT costs and business performance can be difficult to maintain.
* This can make the support of new and expanded business automations an ever-increasing investment. 
* Much of this required investment is funneled into infrastructure expansion because the usage potential of a given automation solution will always be limited by the processing power of its underlying infrastructure.
* Two costs need to be accounted for:
  * The cost of acquiring new infrastructure
  * The cost of its ongoing ownership.
* Operational overhead represents a considerable share of IT budgets, often exceeding up-front investment costs.
* Common forms of infrastructure-related operating overhead include the following:
  * Technical personnel required to keep the environment operational
  * Upgrades and patches that introduce additional testing and deployment cycles
  * Utility bills and capital expense investments for power and cooling
  * Security and access control measures that need to be maintained and enforced to protect infrastructure resources
  * Administrative and accounts staff that may be required to keep track of licenses and support arrangements
 ## Organizational Agility
* Organizational agility is the measure of an organization's responsiveness to change.
* An IT enterprise often needs to respond to business change by scaling its IT resources beyond the scope of what was previously predicted or planned for.
# 2.3 Concepts and Terminology
## Cloud
* A cloud refers to a distinct IT environment that is designed for the purpose of remotely provisioning scalable and measured IT resources.
* The term originated as a metaphor for the Internet which is, in essence, a network of networks providing remote access to a set of decentralized IT resources.
* A cloud was commonly used to represent the Internet in a variety of specifications and mainstream documentation of Web-based architectures. 
* Much of the Internet is dedicated to the access of content-based IT resources published via the World Wide Web.
* IT resources provided by cloud environments, on the other hand, are dedicated to supplying back-end processing capabilities and user-based access to these capabilities.
* Another key distinction is that it is not necessary for clouds to be Web-based even if they are commonly based on Internet protocols and technologies.
* A cloud can be based on the use of any protocols that allow for the remote access to its IT resources.
## IT Resource
* An IT resource is a physical or virtual IT-related artifact that can be either software based, such as a virtual server or a custom software program, or hardware-based, such as a physical server or a network device
* Examples of IT resource:
 * physical server
 * virtual server
 * software program
 * service
 * storage device
 * network device
## On-Premise
* An IT resource that is hosted in a conventional IT enterprise within an organizational boundary (that does not specifically represent a cloud) is considered to be located on the premises of the IT enterprise, or on-premise for short.
* In other words, the term "on-premise" is another way of stating "on the premises of a controlled IT environment that is not cloud-based."
* This term is used to qualify an IT resource as an alternative to "cloud-based." An IT resource that is on-premise cannot be cloud-based, and vice-versa.
* An on-premise IT resource can access and interact with a cloud-based IT resource.
* An on-premise IT resource can be moved to a cloud, thereby changing it to a cloud-based IT resource.
* Redundant deployments of an IT resource can exist in both on-premise and cloud based environments.
## Scaling
*  the ability of the IT resource to handle increased or decreased usage demands.
*  The following are types of scaling:
 * Horizontal Scaling - scaling out and scaling in
  * The allocating or releasing of IT resources that are of the same type is referred to as horizontal scaling
 * Vertical Scaling - scaling up and scaling down
  * When an existing IT resource is replaced by another with higher or lower capacity, vertical scaling is considered to have occurred
## Cloud Service
* A cloud service is any IT resource that is made remotely accessible via a cloud. Unlike other IT fields that fall under the service technology umbrella - such as service-oriented architecture - the term "service" within the context of cloud computing is especially broad.
* A cloud service can exist as a simple Web-based software program with a technical interface invoked via the use of a messaging protocol, or as a remote access point for administrative tools or larger environments and other IT resources.
## Cloud Service Consumer
* The cloud service consumer is a temporary runtime role assumed by a software program when it accesses a cloud service.
# 2.4 Goals and Benefits
## Reduced Investments and Proportional Costs
* Similar to a product wholesaler that purchases goods in bulk for lower price points, public cloud providers base their business model on the mass-acquisition of IT resources that are then made available to cloud consumers via attractively priced leasing packages.
* This opens the door for organizations to gain access to powerful infrastructure without having to purchase it themselves.
* The most common economic rationale for investing in cloud-based IT resources is in the reduction or outright elimination of up-front IT investments, namely hardware and software purchases and ownership costs.
* Common measurable beneﬁts to cloud consumers include:
 * On-demand access to pay-as-you-go computing resources on a short-term basis (such as processors by the hour), and the ability to release these computing resources when they are no longer needed.
 * The perception of having unlimited computing resources that are available on demand, thereby reducing the need to prepare for provisioning.
 * The ability to add or remove IT resources at a ﬁne-grained level, such as modifying available storage disk space by single gigabyte increments.
 * Abstraction of the infrastructure so applications are not locked into devices or locations and can be easily moved if needed.
 ## Increased Scalability
* By providing pools of IT resources, along with tools and technologies designed to leverage them collectively, clouds can instantly and dynamically allocate IT resources to cloud consumers, on-demand or via the cloud consumer's direct conﬁguration.
* This empowers cloud consumers to scale their cloud-based IT resources to accommodate processing ﬂuctuations and peaks automatically or manually.
* Similarly, cloud-based IT resources can be released (automatically or manually) as processing demands decrease.
## Increased Availability and Reliability
* The availability and reliability of IT resources are directly associated with tangible business benefits.
* Outages limit the time an IT resource can be "open for business" for its customers, thereby limiting its usage and revenue generating potential.
* Runtime failures that are not immediately corrected can have a more significant impact during high-volume usage periods.
* Not only is the IT resource unable to respond to customer requests, its unexpected failure can decrease overall customer confidence.
* An IT resource with increased availability is accessible for longer periods of time (for example, 22 hours out of a 24 hour day). Cloud providers generally offer "resilient" IT resources for which they are able to guarantee high levels of availability.
* An IT resource with increased reliability is able to better avoid and recover from exception conditions. The modular architecture of cloud environments provides extensive failover support that increases reliability.
* It is important that organizations carefully examine the Service Level Agreements (SLAs) offered by cloud providers when considering the leasing of cloud-based services and IT resources.
# 2.5 Risks and Challenges
## Increased Security Vulnerabilities
* The moving of business data to the cloud means that the responsibility over data security becomes shared with the cloud provider.
* The remote usage of IT resources requires an expansion of trust boundaries by the cloud consumer to include the external cloud.
* It can be difﬁcult to establish a security architecture that spans such a trust boundary without introducing vulnerabilities, unless cloud consumers and cloud providers happen to support the same or compatible security frameworks - which is unlikely with public clouds.
* The overlapping of trust boundaries and the increased exposure of data can provide malicious cloud consumers (human and automated) with greater opportunities to attack IT resources and steal or damage business data.
## Reduced Operational Governance Control
* Cloud consumers are usually allotted a level of governance control that is lower than that over on-premise IT resources.
* This reduced level of governance control can introduce risks associated with how the cloud provider operates its cloud, as well as the external connections that are required to communicate between the cloud and the cloud consumer.
* Legal contracts, when combined with SLAs, technology inspections, and monitoring, can mitigate governance risks and issues.
* A cloud governance system is established through SLAs, given the "as-a-service" nature of cloud computing. A cloud consumer must keep track of the actual service level being offered and the other warranties that are made by the cloud provider.
## Limited Portability Between Cloud Providers
* Due to a lack of established industry standards within the cloud computing industry, public clouds are commonly proprietary to various extents.
* For cloud consumers that have custom-built solutions with dependencies on these proprietary environments, it can be challenging to move from one cloud provider to another.
* Portability is a measure used to determine the impact of moving cloud consumer IT resources and data between clouds.
## Multi-Regional Regulatory and Legal Issues
* Third-party cloud providers will frequently establish data centers in affordable or convenient geographical locations.
* Cloud consumers will often not be aware of the physical location of their IT resources and data when hosted by public clouds.
* For some organizations, this can pose serious legal concerns pertaining to industry or government regulations that specify data privacy and storage policies. For example, some UK laws require personal data belonging to UK citizens to be kept within the United Kingdom.
* Another potential legal issue pertains to the accessibility and disclosure of data.
# 2.6 From Google's Perspective
* Google is an early pioneer of cloud computing.
* From Google's perspective, there are six key properties of cloud computing:

1. Cloud computing is user-centric
 * Once you as a user are connected to the cloud, whatever is stored there - document, messages, images, applications, whatever - becomes yours. In addition, not only is the data yours, but you can also share it with others. And you should expect that many different devices will be able to access this data.
 
2. Cloud computing is task-centric
 * Instead of focusing on the application and what it can do, when working with the cloud, your focus moves to what you need done and how that application can do it for you. Traditional applications - word processing, spreadsheets, email and so on - are becoming less important than the documents that they can create.
 
3. Cloud computing is powerful
 * Connecting hundreds or thousands of computers together in a cloud creates a wealth of computing power impossible with a single desktop PC.
 
4. Cloud computing is accessible
 * Because data gets stored in the cloud, users can instantly retrieve more information from multiple places. You are not limited to a single source of data, as you are within a desktop PC environment.
 
5. Cloud computing is intelligent
 * With all the data stored on the computers in the cloud, data mining and analysis are necessary to access this information in an intelligent manner.
 
6. Cloud computing is programmable
 * Many of the tasks that are necessary with cloud computing will wind up being automated. For example, to protect the integrity of the data, information stored on a single computer in the cloud will need to be replicated on other computers in the cloud. If one of these computers goes offline, the cloud's programming automatically redistributes load to one of these replicated backups.

# 2.7 From Amazon's Perspective
* From Amazon's perspective, there are six benefits of cloud computing:

1. Trade capital expense for variable expense
 * Instead of having to invest heavily in data centers and servers before you know how you’re going to use them, you can only pay when you consume computing resources, and only pay for how much you consume.

2. Benefit from massive economies of scale
 * By using cloud computing, you can achieve a lower variable cost than you can get on your own. Because usage from hundreds of thousands of customers are aggregated in the cloud, providers such as Amazon Web Services can achieve higher economies of scale which translates into lower pay as you go prices.

3. Stop guessing capacity
 * Eliminate guessing on your infrastructure capacity needs. When you make a capacity decision prior to deploying an application, you often either end up sitting on expensive idle resources or dealing with limited capacity. With Cloud Computing, these problems go away. You can access as much or as little as you need, and scale up and down as required with only a few minutes notice.

4. Increase speed and agility
 * In a cloud computing environment, new IT resources are only ever a click away, which means you reduce the time it takes to make those resources available to your developers from weeks to just minutes. This results in a dramatic increase in agility for the organization, since the cost and time it takes to experiment and develop is significantly lower.

5. Stop spending money on running and maintaining data centers
 * Focus on projects that differentiate your business, not the infrastructure. Cloud computing lets you focus on your own customers, rather than on the heavy lifting of racking, stacking and powering servers.
 
6. Go global in minutes
 * Easily deploy your application in multiple regions around the world with just a few clicks. This means you can provide a lower latency and better experience for your customers simply and at minimal cost.

# 2.8 From Dilbert's Perspective
* Here is the way Dilbert explains the cloud:
 * Pointy Hair Boss: Alan has been out of the workforce for a long time. I need you to ease him back in.
 * Alan: Do you have a binder of the company policies?
 * Dilbert: It's in the Clouds.
 * Alan looks up at the sky.

# 2.9 Video: Cloud Computing Services Models - IaaS PaaS SaaS Explained
* Cloud computing is a paradigm that allow on-demand network access to shared computing resources.
* A model for processing, storing and managing data via the internet.
* 3 delivery models for cloud computing:
 * IaaS - Infrastructure as a Service
 * PaaS - Platform as a Service
 * SaaS - Software as a Service

# 2.10 Infrastructure as a Service (IaaS)
