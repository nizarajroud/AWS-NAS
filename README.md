# AWS-NAS
- **Welcome**
    
    Hi, everyone, I am Julie Elkins,an exam prep curriculum developer here at AWS, and welcome to the AWS Advanced Networking Specialty certification exam prep course.
    
    Preparing for certification exams should always start with understanding the focus and requirements needed for the specific certification. The AWS Certified Advanced Networking Specialty exam validates your ability to design, implement, manage, and secure AWS and hybrid network architectures at scale. In this advanced-level course from Amazon Web Services, you will learn how to assess your preparedness for this specialty certification exam.
    
    Our goal here is not to provide you everything you need to know and understand for each of the domains to pass this certification.
    
    This course is intended to help you assess your readiness for this certification exam. It will provide structure and add clarity and context from each domain, to ensure you are ready to sit and pass your certification exam.
    
    Throughout the course, you will learn how to prepare for the exam by exploring the task statements from the exam guide and how they map to complex networking tasks and to specific areas to study. And you will explore the exam's various domains, and learn how they map to both AWS solutions architect roles and AWS networking specialist roles along with identifying specific areas of study. You will also review sample certification questions in each domain, practice skills with hands-on exercises, test your knowledge with practice question sets, learn strategies for identifying incorrect responses by interpreting the concepts that are being tested in the exam, and you will take a full-length official practice test that will help identify your strengths and weaknesses in each domain area.
    
    This course is intended for those who are preparing to take the AWS Certified Advanced Networking Specialty exam and for those who possess the knowledge, skills, and experience to design, implement, and operate complex AWS and hybrid networking architectures.
    
    There are no specific technical requirements to complete this course or sit for the certification exam, but having a general understanding of concepts from IP, the OSI layers, security, WAN connectivity types, routing protocols, especially BGP, will help you determine your readiness and dive deeper into the concepts. AWS does recommend a minimum of five years using AWS services with a focus on networking and depth in the OSI model.
    
    This exam will test your understanding and ability to implement security best practices, to integrate AWS networking components, automate networks, and deploy at scale. You will also need an understanding of AWS storage options and their features, global enterprise networking requirements, network high availability, and a deep understanding of the TCP/IP stack and IPv4 and IPv6 protocols.
    
    This exam also tests your experience with advanced LAN networking architectures and WAN options, routing architectures, IPv6 network transitions, and experience with network security features such as WAF, IDS, IPS, and DDoS protection. And this course will help you assess if you have the needed knowledge and experience to pass this exam or identify areas to dive deeper. Some key areas to focus on are the AWS networking services such as Amazon VPC, AWS Direct Connect, AWS Transit Gateway, AWS Site-to-Site VPN, Amazon Route 53, and Elastic Load Balancing. But also ensure you have knowledge of the newer networking services too. In this course, we will also walkthrough example questions to help you get a feel for the type of questions you will see on your certification exam.
    
    The overall length, complexity, and difficulty of the questions for specialty certifications tend to be longer and present more complicated scenarios than what you might expect from an Associate-level certification exam. Specialty certification questions are much closer to what you might expect to see on a Professional-level certification exam. Most of the questions involve lengthy scenarios that are usually several sentences to a couple paragraphs in length, and most of the answer choices will be several sentences long as well.
    
    Take your time as you're reading through these longer questions and be sure to process every word and detail that you read. Be on the lookout for repeated sentences across all of the possible answers with just a word or two changed. Those one or two words can make all the difference when it comes to determining which answer is correct and which answer might be a distractor. Always do your best to eliminate these distractors as early as possible to allow you to focus more on the plausible answers and select the best possible answer or answers to each question.
    
    We recommend you take the time and make the effort to understand the content for each domain when studying for the ANS-exam. But also use practice questions to build your reading comprehension skills and identify key words and phrases. You will need skills in advanced networking architectures, subnetting with IPv4 and IPv6, and know how to design and troubleshoot complex routing architectures using static and dynamic networking protocols. These skills will help in the exam to choose the best choice answer for scenarios and to complete tasks for design, implementation, operation, and security along with the use of tools to incorporate automation.
    
    After completing this course and assessing your readiness, it is easy to sign up and schedule your exam by clicking on the link included in the resources for this course. AWS also provides additional resources and you can sign up for weekly exam tips and resources from AWS Training and Certification. Get exam ready with tips on taking your exam, exam guides and sample questions, and opportunities to dive deeper on exam strategies.
    
    In the next video, we will dive deeper into and cover concepts and services you might be expected to know for each domain of the exam guide.
    
    Good luck completing this course and on your certification, too. I will see you in the next video.
    
- **Are you ready?**
    
    Welcome back! Let's quickly run through some of the concepts and services you might be expected to know for each domain of the exam guide.
    
    This certification exam covers a broad range of topics. Your first resource should be the certification exam guide which outlines the certification exam and this course. You will find a link to the exam guide in the course notes. The exam guide references the following four domains.
    
    Domain 1 covers Network Design and this domain covers 30% of the exam content. This domain focuses on designing solutions to integrate edge networking services, DNS, load balancing, routing strategies, and defining logging and monitoring for hybrid and global architectures. The questions from this domain will focus on understanding and designing AWS network concepts, external network connectivity options, and the management, optimization, and troubleshooting of configuration techniques, procedures, and tools to optimize and troubleshoot your network.
    
    Domain 2 covers Network Implementation and this domain covers 26% of the exam content. This domain focuses on implementing routing and connectivity for hybrid environments, connectivity across multiple AWS accounts, Regions, VPCs, and implementing complex hybrid and multi-account DNS architectures. As well as, the automation and configuration of your network. The questions from this domain will focus on implementing network concepts with applications running in AWS so an understanding of AWS services and their relationship to the network is needed and also know how to use CloudFormation to automate the deployment and management of your network and the topologies at scale.
    
    Domain 3 covers Network Management and Operations and this domain covers 20% of the exam content. This domain focuses on maintaining routing and connectivity for hybrid networks, monitoring and analyzing your network traffic to troubleshoot and optimize your connectivity patterns, and there is a focus on optimizing your networks for performance, reliability, and cost optimization too. The questions from this domain will focus on the management, optimization, and troubleshooting tools and practices available in AWS.
    
    Domain 4 covers Network Security, Compliance, and Governance and this domain covers 24% of the exam content. This domain focuses on implementing and maintaining your network to meet security and compliance requirements, validating and auditing your network's security using monitoring and logging, and implementing and securing your data and communications on your network. The questions from this domain will focus on designing and configuring secure and compliant networks while applying AWS best practices for your network configurations.
    
    As we cover each domain, in the next few lessons, be sure to evaluate if you are ready to move forward to sit the exam or if you need more preparation and depth into the topics in each domain. Good luck completing this course. Let's get started with Domain 1: Network Design and I'll see you in the next video.
    
- **Module 1: Network Design**
    - Domain 1 Introduction
        
        Welcome back. First, we'll be starting with Domain 1: Network Design. 30% of the exam content focuses on Network Design so you can expect about 20 questions.
        
        This domain covers everything from edge network service architectures using CloudFront and AWS Global Accelerator to advanced DNS solutions for public, private and hybrid scenarios using Route 53, hosted zones and Route 53 Resolver.
        
        For Domain 1, it's important to understand how to integrate elastic load balancing into your solutions and understand the difference between each of the load balancers in the AWS Elastic Load Balancer family and also know when to use each one. Along with the knowledge of how load balancing works and when to use each type, you'll also definitely want to know how this relates to different layers of the OSI model, because this domain covers designing routing strategies and connectivity architectures that span across multiple Amazon VPCs, Regions and AWS accounts.
        
        Here's a quick exam tip. You'll be expected to know how to configure resource sharing across accounts using AWS Resource Assets Manager. You'll also be expected to know when to use VPC peering, AWS Direct Connect, AWS Site-to-Site VPN, Transit Gateway, and AWS Private Link when facilitating communications between VPCs, Remote Clients and private or on premises networks.
        
        The first domain for the certification Network Design is broken into six task statements.
        
        The first task statement is design a solution that incorporates edge network services to optimize network performance and traffic management for global architectures. This will involve looking at designs based on patterns for content distribution and global traffic management using CloudFront and Global Accelerator, integrating services such as Amazon API Gateway and Elastic Load Balancing and evaluating requirements of inbound and outbound traffic to ensure the design is an appropriate content distribution solution.
        
        The second task statement is design DNS solutions that meet public, private, and hybrid requirements. This involves knowledge of DNS protocols, DNS logging and monitoring, as well as the features of Amazon Route 53.
        
        The third task statement is design solutions that integrate load balancing to meet high availability, scalability, and security requirements.
        
        The fourth task statement is define logging and monitoring requirements across AWS and hybrid networks.
        
        The fifth task statement is to design a routing strategy and connectivity architecture between on premises network and the AWS Cloud.
        
        The sixth task statement is design a routing strategy and connectivity architecture that includes multiple AWS accounts, AWS Regions and VPCs to support different connectivity patterns.
        
        Again, refer to the exam guide and scan here for a link to that exam guide.
        
        Over the next several videos in this module, I will address each task statement individually breaking down the knowledge and skills expected of you to be successful. Let's start to evaluate your readiness for the exam in the next video.
        
    - Edge network services
        
        Welcome back!
        
        Let's begin with the first task statement from Domain 1. Designing solutions that incorporate edge network services to optimize user performance and traffic management for global architectures.
        
        This task statement will have four topics that we need to know and understand. Designing your network and your environment to incorporate edge networking services can help to optimize user performance and traffic management for your global network designs. You'll want to know the AWS services that can assist for this, including CloudFront, Global Accelerator, the elastic load balancing family, and API Gateway.
        
        When examining the first task statement, be aware that the exam will rarely focus on a single service. This exam requires you to understand multiple services in order to implement the best network design.
        
        Let's dive deeper.
        
        The exam guide gives us four topics for the first task statement of Domain 1. Make sure you understand each.
        
        Topic 1: design patterns for the usage of content distribution networks. For example, CloudFront and AWS WaveLength.
        
        Topic 2: design patterns for global traffic management. A key service here is Global Accelerator.
        
        Topic 3: integration patterns for content distribution networks and global traffic management with other services. This includes using Elastic Load Balancing and API Gateway for fault tolerance.
        
        And finally, the fourth topic, evaluating requirements of global inbound and outbound traffic from the internet, to design an appropriate content distribution solution. Amazon CloudFront might be useful here too.
        
        Let's dive deeper into each topic and go back to our first topic, design patterns for the usage of content distribution networks.
        
        Which AWS service do you think you need to know?
        
        It's definitely CloudFront. Make sure you understand the components of a CloudFront distribution, CloudFront for caching content, CloudFront for streaming content, and Lambda@Edge. AWS edge-computing services provide infrastructure and services that move data processing, analysis, and delivery as close to the requestor or customer as necessary.
        
        So, how would you develop a design pattern for using CloudFront?
        
        Well, first you need to know how your content is being accessed. To do this, you'll want to understand who and/or what needs access, and how will they access the service and your architecture. For the exam, understand how you can restrict access. You might use an ELB, specifically an application load balancer with an attached security group to limit the types of traffic that reaches your application.
        
        Another way to secure access is to use an AWS Web Application Firewall, or WAF, to allow or block requests by origin, size, or to detect malicious SQL code or scripting. Use Shield or Advanced Shield to mitigate a distributed denial-of-service attack. And you might also consider geographically restricting access to your content and using field-level encryption to protect your data.
        
        While we're thinking about application load balancers, you'll want to understand listener rules, condition types, and the features or differences between the other members of the elastic load balancing family, especially the newest, the Gateway Load Balancer.
        
        Understand TCP passthrough, request headers, such as X-Forwarded-For and Proxy Protocol version 2, as well as content distribution, web protocols like HTTP and HTTPs, caching, and how to secure your origin or load balancer.
        
        You'll want to understand the use cases for CloudFront, how CloudFront works with dynamic and multiple origins, how to create a distribution and types of origins, how to serve private content with CloudFront, and how and why you would invalidate objects from CloudFront.
        
        For our second topic, design patterns for global traffic management, you'll need a thorough understanding of the AWS Global Cloud Infrastructure and the fundamental networking components of an Amazon VPC.
        
        As you are migrating to AWS, you'll want to ensure your network performs with higher levels of availability and performance using the AWS global infrastructure and multi-Regions. In this situation and for the exam, you need to know how to plan for data consistency, how to distribute and manage traffic across multiple Regions, software stacks, A/B testing, global load balancing, failovers, and disaster recovery too.
        
        One AWS service that stands out for this topic is Global Accelerator, because it can help to simplify traffic routes across applications in multiple Regions. A design principle of the reliability pillar from the AWS Well-Architected Framework is to design systems that can automatically recover from failure. Network architects can build highly resilient, multi-Region designs using network services such as Amazon Route 53 and Global Accelerator.
        
        These services can detect failure and route client traffic away from it, increasing the availability. In a similar fashion, traffic flows within an Amazon VPC can route around failure by updating subnet route tables to direct that traffic. Be sure to brush up on options for configuring an Amazon VPC, such as subnetting, DHCP option sets, route tables, network-access control lists, and security groups.
        
        As an architect, it's also necessary to know how to best provide connectivity beyond a VPC, using services and resources such as NAT gateways, internet gateways, egress-only gateways, and virtual private gateways. For the exam, you'll want to understand how to manage your traffic with Global Accelerator, along with the AWS global infrastructure, Regions, Availability Zones, Amazon VPC, and how to integrate services.
        
        The third topic is how to integrate patterns for content distribution networks and global traffic management with other services. Continuing with ELB, AWS Elastic Load Balancing offers health-checking capabilities that can validate the health of compute components using a variety of network protocols, such as TCP, HTTP, HTTPS, and SSL.
        
        The metrics generated through ELB monitoring is logged by Amazon CloudWatch. CloudWatch provides the capability to create operational alerts that can trigger automations to remediate failures. API Gateways also fall under this topic, specifically API design and functionality.
        
        Some key questions to consider are, what's the common protocol used with an API Gateway, and what methods can be used to secure HTTP? Ensure you understand how you can expose different types of applications running on EC2 instances or ECS, to the internet and allow direct communication with any HTTP/HTTPs enabled services like Amazon S3 and Amazon DynamoDB.
        
        An API Gateway also allows us to send queries to Lambda functions that are not exposed to the internet. In this design, do you know what is the entry point to your Lambda environment?
        
        Also, know how this gives you the ability to expose services completely external to AWS.
        
        For the exam, understand the following: why and how you would use HTTPS with CloudFront, how does health checking work with elastic load balancing, and how it can be used with Route 53? What are the components that can be configured with elastic load balancing, API designs, functionality, and gateways?
        
        Also, know what AWS services sit inside and outside of your Amazon VPC.
        
        For the fourth topic, know how to evaluate requirements of your global inbound and outbound traffic from the internet, and how to design an appropriate content distribution solution. Your design should always start with your requirements first, including current and possible future requirements too. Connectivity and network communication issues from the complex nature of interconnectivity between services are common in real-world scenarios. These usually arise when communication needs to occur inside your Amazon VPCs, between peered VPCs, working with VPNs, or Direct Connect to on premises network, and connecting to CloudFront too.
        
        You'll want to know the AWS resources that provide data sources to help increase visibility into network operations. These can help with network-administration tasks such as troubleshooting network connectivity issues. You'll also want to know what logs are needed to add more visibility. Make sure you dive deeper into VPC flow logs, access logs for your application load balancer, traffic mirroring, and CloudFront logs too.
        
        Also, for the fourth topic, you need to understand how to configure CloudFront to create log files that contain detailed information about every user request that's received.
        
        Some questions to consider include, are these access logs available for both web and real-time messaging protocol distributions? And how do you incorporate and push metrics to CloudWatch to meet your requirements of optimizing global inbound and outbound traffic?
        
        Additionally, network administrators need to understand where these data sources are stored, how frequently data is written to them, and what information they contain to be effective at troubleshooting.
        
        Also, dive deeper into application workloads, such as high-performance computing that may require lower latency and high bandwidth network connections between compute nodes. AWS provides configuration options to meet the needs of these workloads, such as placement groups, jumbo frames, and elastic network adapters. Consider how you would design for high-performance computing workloads to achieve your desired network performance.
        
        Another example could be, how would you design a solution for a company that has a subscription-based platform in AWS that uses a paywall for all new content?
        
        You could create an ECS cluster to host the application and service the content. You could also configure Amazon Cognito to handle registrations and management, and you could configure CloudFront to serve the static and dynamic content.
        
        In this design, consider the question, what is the most efficient additional solution with minimal latency that you could add to deny unauthorized user? Would you use the AWS IAM Identity Center, which is the successor to AWS Single Sign On, and Cognito, or maybe Origin Access Identities, or Signed URLs, or even Lambda@Edge?
        
        Moving on, for the exam, understand logs that can be generated by which AWS services, what logging services aggregate them, what tools are available to analyze and alert, and how to be notified or set up automation.
        
        Let's dive into the second statement task from the Network Design Domain.
        
        Task Statement 1.2 Design DNS solutions.
        
        And I'll see you in the next video!
        
    - DNS Solutions
        
        Welcome back. Let's dive into the second task statement, designing DNS solutions that meet public, private and hybrid requirements.
        
        This task statement will have two topics that we need to know and understand. The first is knowledge of DNS protocols, DNS logging, and monitoring. And the second is Amazon Route 53 features. Let's review both.
        
        For the first topic in this task statement, and before you sit for the exam, you'll need a solid understanding of the components of DNS and how it works, including the different record types, and also how DNS works with EC2.
        
        Amazon will automatically assign host names to your EC2 instances when you set the enabled DNS support, and enable DNS host names options to true in your VPC. Amazon handles the DNS creation and configuration. However, customized capabilities are limited. DNS names are provided for both the private and public IP addresses for your EC2 instances.
        
        But if you need customized DNS names, you can use Route 53. Route 53 is a highly available and scalable cloud DNS web service that gives you more control including CNAME creation and management. And for this exam, it is important to have a solid understanding of all of the features of Route 53, in addition to the characteristics of EC2 host names.
        
        Also, be aware of the limitations when connecting over the internet. Knowledge of public versus private DNS, configuring and deploying VPNs, virtual private gateways, and Direct Connect are needed, as well as how to secure your VPNs and Direct Connect connections. For example, how can you add and delete public keys from the top level registry for your domain register In Route 53? You can protect your domain from attacks to intercept DNS queries that would return their own IP addresses by configuring DNSSEC. This protocol helps to secure your DNS traffic and you should see questions on the exam around this.
        
        Another important tip is to remember, when using Route 53 private hosted zones, a private hosted zone must be connected to a specific VPC to ensure traffic and resources are not accessible outside of your VPC.
        
        Overall, you wanna make sure you know how DNS works with your EC2 instances and within your VPC. Let's take a moment to talk about Amazon Route 53 features. Route 53 performs three main functions.
        
        First domain registration. Make sure you know how to create, but also manage domains.
        
        Second, DNS as a service. Make sure you have a solid understanding of DNS records, timers, DNSSEC, DNS delegation, and zones.
        
        And third, DNS health checking.
        
        Some questions to consider around DNS health checking include what are the benefits of DNS health checks? How do they help with failovers? How can you integrate other AWS services with your health checks to add visibility?
        
        Route 53 is featured heavily throughout the official exam guide, having a solid understanding of DNS fundamentals, registrations, configurations, integrations, troubleshooting, and security is crucial.
        
        For the exam, understand DNS, the features of Amazon DNS server, the differences between the self-managed DNS server on EC2, and Route 53. This includes hosted zones in supporting record types, Route 53 routing policies, Traffic Flow, Route 53 Resolver, Route 53 Resolver DNS Firewall, Route 53 Application Recovery Controller, DNSSEC, CloudFront, and S3 Zone Apex Support, as well as load balancing integration, and many more.
        
        Let's get started with the third task statement from the network design domain.
        
        Task statement 1.3, Design solutions that integrate load balancing.
        
        Scan the QR code for a link to the exam guide to follow along, and I'll see you in the next video.
        
    - Elastic load balancing
        
        Welcome back, let's dive into the third task statement.
        
        Designing solutions that integrate load balancing to meet high availability, scalability and security requirements.
        
        This task statement has 10 topics that we need to understand. An advantage of using AWS is the ability to provide high availability, reliability, and elasticity which ensures a more consistent experience for your users in traffic. And this is where the AWS load balancing family comes in and is the focus for this task statement.
        
        And for this exam, you must have knowledge of load balancing technologies and how different types of networking traffic can be distributed across the servers running your applications.
        
        This includes a clear and deep understanding of Amazon EC2 common network concepts and supporting technologies such as local host name, IP version four, IP version six, network configurations, EC2 metadata, and so on.
        
        And as we have mentioned, AWS has a family of load balancers which all deliver high performance, highly available, highly scalable, load balancing based solutions in different ways. It's important to also understand load balancer concepts and configurations. Are you familiar with the configuration options for load balancers as well as load balancer target groups? Do you know how to integrate load balancers with CloudWatch and auto scaling?
        
        After attaching a load balancer to your auto scaling group ensure you can configure your auto scaling group to use elastic load-balancing metrics such as the application load balance or request counts per target to scale the number of instances in the group as demand fluctuates. And remember, you can add elastic load balancing health checks to your auto-scaling group so that Amazon EC2 auto scaling can identify and replace unhealthy instances based on these additional health checks.
        
        What is another configuration design? How about creating a CloudWatch alarm that notifies you if the healthy host count of the target group is lower than allowed? You'll most likely see questions with scenarios that need to balance a load between instances or clusters as the connections increase or decrease.
        
        Let's dive deeper into the following topics regarding load balancing for the exam.
        
        Do you know how load balancing works at layer three, four and seven of the OSI model?
        
        What are the different load balancers within the ELB family?
        
        How can each fit the requirements for different network designs or support high availability and security requirements?
        
        Do you know the use cases and different connectivity patterns for each ELB type?
        
        Pay special attention to the newest load balancer. The gateway load balancer. The gateway load balancer helps to deploy inline appliances for north, south and east west traffic patterns. Get specific and dive deep into each type of load balancer.
        
        More questions to consider.
        
        Which load balancers can be restricted to VPC internal traffic only?
        
        If an ELB is accepting external traffic what considerations must be addressed?
        
        And make sure you understand the factors that impact an application's ability to scale when it's behind an ELB. Also, when deploying an ELB and configuring the target groups, ensure that you understand the type of traffic that the ELB will be supporting.
        
        Ask yourself, how will this traffic impact the available configuration options such as the session affinity, proxy protocol, routing, or cross zone load balancing? What impact will your decisions about encryption and authentication have on your applications' performance?
        
        Will you deploy TLS pass through? And finally, ask yourself, before you enable proxy protocol version two in your network load balancer configuration. What must you ensure can process your proxy protocol headers? And dive deeper into what AWS services integrate with an ELB. Key services for this are Global Accelerator, CloudFront, EKS, AWS Certificate Manager, and make sure you understand each of these services and understand how to integrate and configure each.
        
        In the last lesson we mentioned the importance of understanding how to integrate load balancers with Route 53 and Route 53 Resolve for DNS firewall.
        
        But do you know how to integrate your load balancer with AWS WAF?
        
        Do you know how to set up sequel injection filters for a query string and use that filter to create a rule to block requests?
        
        If you're supporting an application hosted on EKS, what impact will having or not having an AWS load balancer controller for Kubernetes Clusters have?
        
        The AWS load balancer controller now features in the exam and it can create a network load balancer to balance your network traffic to pause deploy by EC2 IP and instance targets or to Fargate IP targets.
        
        To deploy the load balancer controller, you'll need to meet certain requirements. Do you know what those requirements are? In your AWS Global Accelerator configuration what choices do you have for an endpoint type? It could be a network load balancer, an application load balancer, EC2 instances, or elastic IP addresses.
        
        If you search the exam guide for load balancer, it appears more than anything else. So make sure to dive deep and be ready to select the best choice load balancer based on use cases. And also know how to integrate auto scaling with load balancing solutions and also with existing application deployments.
        
        Let's get started with the fourth task statement from the network design domain, task statement 1.4. Define logging and monitoring requirements.
        
        Scan the QR code for a link to the exam guide to follow along and I'll see you in the next video.
        
    - Logging and monitoring
        
        Welcome back. Let's dive into the fourth task statement, defining logging and monitoring requirements across AWS and hybrid networks. This task statement is to define logging and monitoring requirements across AWS and hybrid networks and has two topics that we need to understand.
        
        The two topics focus on the AWS services that provide a user visibility into their AWS architecture and access logging. CloudWatch offers metrics, agents, logs, alarms and dashboards, AWS Transit Gateway AWS Transit Gateway Network Manager VPC Reachability Analyzer, VPC flow logs, and VPC traffic mirroring each provide unique insights into what traffic crosses your network and can help identify sources of congestions or network problems. Logging who is accessing services such as EOB CloudFront and Route 53 is useful for understanding whether you are complying with the access requirements.
        
        Let's dive deeper into each topic for this task statement.
        
        For the first topic, be familiar with AWS services that enhance your visibility in your network design and traffic. Understand the basics of performance monitoring, metrics analysis, and network traffic flow to understand is your system up or down? Is it fast or slow? Can you easily spot problems that arise and can you respond and resolve those problems quickly?
        
        Observability is how well you can understand what is happening in your network by collecting metrics, logs and traces, as your environment grows, observability can be difficult to achieve whether you're in AWS or on premise. To achieve operational excellence, you must understand your network performance. How do you get insights into the state of your network? And application monitoring is an activity that ensures your network is observable which enables you to detect and investigate problems. Real time detection should be proactive and include alarms when performance thresholds are breached to help you quickly investigate and understand the root cause. How do you add the functionality of alarming automation and remediation? Make sure you know how to configure and push metrics to CloudWatch, but also how to use custom metrics from when you need additional insight beyond standard CloudWatch metrics.
        
        This topic also covers understanding that today's global networks include resources that are located in AWS and on premises, to monitor your entire global network, metrics and data are needed from all locations. What AWS service can provide a single global view of your private network? The answer is AWS Transit Gateway Network Manager. Make sure you understand how to register your AWS Transit Gateways and how to define your on-premises resources to configure your software defined wide area network devices to connect with Transit Gateway Network Manager Transit Gateway Network Manager performs three main functions you need to know and understand for the exam.
        
        First, centralized network monitoring which adds the ability to visualize your global network in a topology diagram and also on a geographical map. Second, global network visibility to help review utilization metrics such as bites in and out, packets in and out, packets dropped, and alerts for changes in the topology, routing up down connections and more easily manage your entire global network. And third SD WAN integration. You might be using your existing SD WAN devices from your on premises connecting to a transit gateway. Transit Gateway Network Manager SD WAN integration adds a unified interface to manage your global networks across AWS and on premises locations.
        
        Two, monitoring global networks include both resources located on premises and in AWS. Like we touched on earlier, you'll wanna collect metrics logs, and traces from the whole environment. Network Manager an add a single global view. Besides adding visibility, what use cases would you choose to add Transit Gateway Network Manager into your network design? Can you configure automatic event notification to help identify global network issues? And if so, how? Check out Network's Managers event notifications. Also, when you choose to use your existing SD WAN devices a large number of prefixes are advertised to Transit Gateway.
        
        Do you know how to use the Transit Gateway Connect feature along with AWS Direct Connect to advertise a higher number of prefixes or to increase bandwidth? And do you know how to use multi-protocol BGP support for route exchange? Another service that provides visibility between services and resources within a VPC is VPC Reachability Analyzer.
        
        What visibility does this add?
        
        Well, it is a configuration analysis tool used to perform connectivity testing between a source and destination resources in your VPC. It is a great tool to add visibility if your paths are blocked by configuration issues in a security group network, ACL route table, or load balancer.
        
        For the exam, understand use cases and know that Reachability Analyzer adds three functions. First, to troubleshoot connectivity issues calls by network misconfiguration, second to verify that your network configuration matches your intended connectivity.
        
        And third, to automate the verification of your connectivity intent as your network configuration changes. Also dive deep and know how VBC Reachability Analyzer performs connectivity testing between a source and destination.
        
        Here are some questions to consider:
        
        Can your source and destination resources be in different multi regions?
        
        Can analysis occur over peering connection?
        
        What AWS resources are supported by VPC Reachability Analyzer?
        
        Understand the limitations as well as the resources supported. VPC flow logs and AWS Traffic Mirroring. Also add visibility and help to troubleshoot problems. You may see questions on how to use flow logs and Traffic Mirroring to provide insights into your network traffic. Sometimes when we are setting up our network security the flow of traffic is not passing through the target as expected. Ensure you know how to troubleshoot traffic flow. Also know what information is captured using VPC flow logs and Traffic Mirroring. Does the flow log data you capture affect your network throughput or latency? For the exam, be able to read flow logs and know the limitations.
        
        Also know that flow logs do not perform packet inspection but Traffic Mirroring can help inspect your traffic. Flow logs are not intended for network performance collection but CloudWatch can be used for performance metrics. But where are these data flow logs stored? CloudWatch or Amazon S3? What are the main tasks that flow logs can help diagnose monitor, and determine? Let's dive deeper into Traffic Mirroring and what you'll need to know.
        
        Do you know how to copy your network traffic from an Elastic Asset Network interface and send the traffic to out of bound security and monitoring appliances for content inspection, threat monitoring and troubleshooting?
        
        Here are questions to consider.
        
        What are the key concepts for Traffic Mirroring?
        
        Can the security and monitoring appliances be deployed as individual instances or a fleet of instances behind a network load balancer or a gateway load balancer?
        
        Does Traffic Mirroring support filter and packet truncation ensure you know the three use cases to add visibility with Traffic Mirroring content inspection threat monitoring, and troubleshooting. Another question to ask yourself is, do flow logs capture mirror traffic?
        
        For the second topic, understand access. Logging for load balancers, CloudFront, API gateway and Route 53. In AWS, all assets, creations and modifications must be performed through an API. This makes APIs a single point of control with regards to event visibility and audit compliance through logging.
        
        For this exam, you need to know what AWS services log API calls and what AWS service logs the effects or results of API calls, what AWS service logs Amazon EC2, ELB, CloudFront and Route 53 events? And what AWS service collects and logs network traffic records? Make sure you understand which AWS services to configure and use to get the appropriate logs and visibility into your network and design.
        
        When you're configuring, monitoring, and alerting for your network remember that login capability must be responsive secure and scalable, and know where you can send logs. Also, remember that different logs have different delivery latencies and may require a separate stream and logging should be enabled in every region.
        
        Some questions to consider are how would you design an improvement to your network monitoring for your private hosted zone in Route 53?
        
        Would you configure health checks for your record sets? And if so, would that configuration be in the same zone of your EC2 instances? And what metric would you want to watch?
        
        Would you use Route 53 CloudWatch or AWS Personal Health Dashboard?
        
        And what metric would you track? Airport allocation, status check failed, or network in?
        
        Monitoring is a key component to track your network performance, resource usage, and cost too it provides an insight to the state of our network. Along with alarming and automation. Many organizations require that networking costs for their hybrid architecture should be monitored.
        
        Do you know which Direct Connect billing charges to monitor, data transfer out, instance hours, data transfer in, BGP hours or port hours?
        
        For the exam, also, understand how to access logs for load balancers, CloudFront, API gateway, and Route 53 as well as other AWS services, ensure you know how to identify the logging and monitor requirements, how to recommend appropriate metrics to provide visibility of the network status, and how to capture baseline network performance. Ensure you have depth in Transit Gateway Network Manager as it features in domain one, three, and four. Transit gateway is a service that's used in many VPC interconnectivity architecture.
        
        Also, take the time to understand how to add the visibility to your network design. You will see questions covering complex network design scenarios and you must know how to design, configure, identify, and resolve network connectivity issues.
        
        Let's get started with the fifth task statement from the network design domain, task statement 1.5, design a routing strategy and connectivity architecture.
        
        Scan the QR code for a link to the exam guide to follow along and I'll see you in the next video.
        
    - Hybrid routing
        
        Welcome back, let's dive into the fifth task statement for domain one on hybrid routing. Design a routing strategy and connectivity architecture between on-premises network and the AWS Cloud. This task statement contains topics and knowledge areas that we need to understand for hybrid connections. Connecting on premises and AWS networks requires depth in connectivity options, VPNs, and multi-protocol routing. Experience with configuring hybrid networks using AWS and your existing network allows for a better understanding of how these systems interact.
        
        For connectivity, understand the options available to pass traffic between VPCs and private networks. Know how to anticipate network traffic patterns and configure the services and equipment to support that hybrid network. You'll also need to understand how the context of routing comes into play after the connectivity is set. A focus here is on protocols like IP and BGP that will enable connectivity with and between autonomous systems. A big part of this exam is routing, not only the fundamentals but in-depth knowledge is needed to design routing in a hybrid environment. Make sure you understand how to identify hybrid connectivity requirements and how to design hybrid connections between AWS and on premises networks. It is also necessary to understand how the traffic patterns you choose to model will influence your traffic routing decisions, fault tolerance, and redundancy.
        
        All of these items will determine how you integrate your SD-WAN and AWS services into your design. For the exam, understand the features of an AWS-managed VPN, both site-to-site and client. What is the difference and use cases for both AWS Site-to-Site VPN and AWS Client VPN? Do you know how to configure a VPN connection on the AWS side and the customer side? Which VPN configurations meet the requirements of AWS high availability models? There are several VPN connectivity options to connect your VPC and remote networks.
        
        Take the time to learn the steps required to establish a VPN connection to a virtual gateway, the different VPN termination options available and specific ones for terminating a VPN on an Amazon EC2 instance. There are four termination options on the AWS side. The VPN performance and scalability will vary based on which option you choose.
        
        For each option it's important to understand the bandwidth and scalability characteristics. What AWS service can help to integrate and support GRE and BGP protocol in your network appliance? We mentioned this service in our last lesson, transit gateway connect.
        
        Does this provide higher bandwidth compared to a VPN connection? Yes, it does.
        
        Lastly, take note of the offered VPN failover and scaling architectures. Understand the redundant connections for failover and scaling considerations using transit gateway, client VPN, and Site-to-Site VPN connections. You can also use Direct Connect to create a dedicated private connection from a remote network to your VPC. You can combine this connection with an AWS Site-to-Site VPN to create an IPsec-encrypted connection. Another hybrid connectivity type is AWS Direct Connect. AWS Direct Connect establishes a dedicated network connection from your on premises environment to AWS, providing consistent performance. It is also the shortest path to your AWS resources. Having a firm grasp of the physical elements of an AWS Direct Connect connection, the process to establish connectivity, configuring BGP, and establishing path selection is fundamental for this type of hybrid network connection.
        
        What are the prerequisites needed to meet the minimum Direct Connect connection requirements?
        
        How would you design a Direct Connect connection from on premises to allow access to various EC2 instances in several VPCs?
        
        What if that design also needs to incorporate fetching data store in S3 buckets in multiple Regions?
        
        Ensure you dive deeper into multi-Region access points in S3. The AWS Direct Connect Resiliency Toolkit helps to provide and achieve a highly resilient network connection between AWS and your on premises.
        
        Make sure you understand the benefits of this toolkit, such as, redundant connections, speed, LAG summary, and tests to confirm the resiliency of your configuration. What are the resiliency patterns available?
        
        There are four, Classic, Development and Test, High Resiliency, and Maximum Resiliency.
        
        Also understand how to add redundancy and cost savings to your hybrid network model by combining AWS Direct Connect with a VPN. Will this redundant design create an IPsec-encrypted connection? Yes, when using AWS Direct Connect and AWS Site-to-Site VPN, you can combine one or more AWS Direct Connect dedicated network connections with Amazon VPC VPN. This combination provides an IPsec-encrypted private connection that also reduces network costs, increases bandwidth throughput, and provides a more consistent network experience than internet-based VPN connections. You should know that Direct Connect does not encrypt your traffic in transit by default, but it does provide transit encryption options.
        
        How would you design a hybrid cloud architecture with an on premises network and a VPC connected with a Direct Connect connection using a private virtual interface that needed a highly available Amazon AppStream solution to communicate both with your AWS resources and the on premises data center while providing employees instant access to their virtual desktops anywhere and anytime that access is needed?
        
        Here is a hint, you could set up two subnets in your VPC and launch another private virtual interface on your Direct Connect connection to allow the on premises users to connect to the AppStream's Interface VPC endpoint.
        
        As we mentioned, a few key elements for hybrid connectivity in an AWS environment include routing fundamentals. For example, being able to cite the differences between dynamic and static routing or the features of BGP protocol.
        
        Can you define the layer one and layer two networking for physical interconnects in a Direct Connect configuration?
        
        Answering this question might encompass jumbo frames, a definition of the term VLAN, or what a link aggregation group is. How would you design four Direct Connect connections for two data centers to connect to an Amazon VPC?
        
        How do aggregate multiple connections at as single Direct Connect endpoint to have a single managed connection? Understanding network encapsulation and encryption will provide a good foundation for the more advanced topics for this part of the exam.
        
        In AWS, you no longer need to manage and operate multiple IPsec connections between your on premises appliances and transit gateway. You can integrate Transit Gateway Connect which is an attachment that supports GRE for higher bandwidth performance compared to VPN and also supports BGP for dynamic routing.
        
        Also knowing how AWS accounts allow resources sharing and how to support overlay networks will help as well. Routing features heavy on this exam and in Domain one, two, and three of the exam guide.
        
        Let's get started with the sixth task statement from the Network Design domain.
        
        Task Statement 1.6, design a routing strategy and connectivity architecture.
        
        Scan the QR code for a link to the Exam Guide to follow along. And I'll see you in the next video.
        
    - AWS connectivity
        
        Welcome back! Let's dive into the sixth task statement. Design a routing strategy and connectivity architecture that include multiple AWS accounts, AWS Regions, and VPCs to support different connectivity patterns.
        
        This task statement has three topics that we need to understand. Connectivity for private networks, hybrid connectivity options, and centralized or shared services. When connecting private networks, an older approach would be to create a private connection, usually using a VPN establishing a layer 3 connection between the networks. AWS provides different options for connecting VPCs, AWS accounts, and on premises with AWS. Since the connection is most likely using layer 3 networking, you'll also need to understand routing and subnetting.
        
        While not as widely implemented as IP version 4, IP version 6 should be a focus of study for this exam. And in the future, you will see IP version 6 more and more. In addition to hybrid connectivity options, AWS provides services based on your connectivity requirements too.
        
        For example, VPC Peering, transit gateway, PrivateLink, and so on. What are the different connectivity options for network to Amazon VPC, Amazon VPC to Amazon VPC, and software remote access to Amazon VPC? You can connect across Regions, within Regions, to VPC interface endpoints, and VPC endpoint services.
        
        For the exam, you need to dive deeper and understand how VPC endpoints scale and add more flexibility than VPC peering. Specifically, PrivateLink. Not only can you improve the security of your VPC by using endpoints, you can configure auto-scaling to use PrivateLink interface endpoints. This will enable private access within your VPC for any API calls to the Autoscaling service. Do VPC endpoints also allow overlapping IP addresses? Yes, PrivateLink provides connectivity for resources with overlapping IP address ranges.
        
        Ensure you understand how to design and configure solutions for IP subnets with IP address overlaps. How do you address overlap with an on premises network and AWS? Could you use AWS PrivateLink and Direct Connect and/or a VPN to address overlapping?
        
        Also, know how would you use NAT Gateway for overlap. Do you know how to configure your outbound VPC security group rules to use the AWS-managed prefix list to connect to a Gateway endpoint? If so, can you reference AWS-managed prefix lists in the subnet route tables too? Plus, be prepared for more scenario questions on centralized or shared services VPCs. What are the advantages of VPC sharing? There are multiple scenarios where you need to access services in a different VPC. Depending on your requirements, your VPCs and services may need to be segmented further by specific functions, such as networking, security, tools, incident response, and so on.
        
        For this exam, you must know and understand the different connectivity patterns and use cases for services such as VPC Peering, transit gateway, and AWS PrivateLink. Ensure you're familiar with the capabilities AWS offers for sharing resources between VPCs. Do you know the advantage of each capability? When passing data between VPCs, you may run into one or more issues involving IP subnetting, so ensure you know the common conflicts and solutions.
        
        For example, how would you resolve an IP address overlap between VPCs? Furthermore, take time to investigate use cases for connecting multiple VPCs. Which services are most appropriate for which scenario? When would you use VPC peering over transit gateway? What if you need to support inter-Region peering across multiple AWS Regions for a hybrid network architecture that consists of regional on premises data centers and hundreds of VPCs?
        
        Here's a hint, you could use transit gateway to connect the geographically disperse VPCs and remote networks to create a global network transit center.
        
        Are you comfortable in your ability to design, implement, and configure this architecture?
        
        When is PrivateLink the best choice?
        
        What is the use case for sharing a VPC in a multi-account setup? Thinking back on managing IP overlaps, when would NAT be a better choice than PrivateLink or Transit Gateway?
        
        And this wraps up the Network Design Domain 1. It is the largest domain, so if you need to re-watch any of the lessons to ensure you are ready for this domain, please do so.
        
        You can also visit the Exam Guide by scanning the QR code.
        
        Up next, you'll engage in a practice activity. After that exercise, we'll get started with an introduction to Domain 2: Network Implementation.
        
    - Walk through Question 1
        
        Hi and welcome back to our first walk through question. These walk through questions are meant to assist you in a few ways and will give you an opportunity to see the types of questions you should expect to see in the exam. These questions are not pulled directly from the certification exam, but they are similar to the types of questions on the actual certification exam and will give you opportunities to explore this style of questioning. You will also get to work through methods to help you select the best choice answer, especially for AWS multiple-choice questions. These walk through questions are meant to help you learn how to identify keywords and phrases and also to quickly identify distractors, again so you can choose the best choice answer for each question. Practice exams are great to help you identify the areas you are confident in and reinforce your knowledge, but they can also help you to identify gaps in your knowledge.
        
        As we walk through each of these questions, we will start by reading the question, then we will identify keywords and phrases, and then do the same for each answer. Feel free to pause the video and see if you can identify the correct response yourself. After you have chosen your choice answer, we will walk through each answer and talk about why they are correct or incorrect.
        
        Let’s dive into our first question.
        
        A company has deployed an application to several regions in AWS. Each regional application deployment has a public API endpoint that allows the application to be accessed in close proximity to the users.
        
        The company is using Amazon Route53 to manage DNS records for the application. The company needs to design a solution that will ensure clients are always accessing the API endpoint that will provide the most performant response.
        
        Which of the following configurations would satisfy the requirements? (Choose one)
        
        So for this first question, what key words and phrases can you identify? The question is asking which of the configurations satisfy the requirements for high availability and high performance of the API endpoint for an application deployed in several Regions.
        
        So now let's look at the answers:
        
        A is Configure the API endpoint Route 53 records with a latency-based routing policy.
        
        B is Configure the API endpoint Route 53 records with a geo location routing policy
        
        C is Deploy a Network Load Balancer (NLB) in front of the APIs to increase performance.
        
        D is Deploy a Gateway Load Balancer (GLB) in front of the APIs to increase performance.
        
        So answer A recommends configuring the API endpoint Route 53 records with a latency-based routing policy. For an application that is hosted in multiple AWS Regions, latency-based routing can improve performance for the application users by serving requests from the AWS Region that provides the lowest latency, thus ensuring highest performance. This is the correct answer, so if you choose A, GREAT JOB!!, but before you select this answer and move on, make sure you review each answer to ensure you choose the best choice answer.
        
        Answer B recommends geo location routing which allows for serving traffic based on the geographic location that DNS queries. This may also sound like a great answer, but we need to dive deeper into the differences between latency routing and geo location routing policies. Both policies will route the traffic request to the nearest resource from where the query originates. Remember the question asks for both high availability and high performance. Geolocation routing allows for serving traffic based on the geographic location that DNS queries originate from. Geolocation routing does not guarantee the lowest latency and does not ensure highest performance.
        
        Answer C recommends deploying a Network Load Balancer (NLB) in front of the APIs to increase performance. A NLB functions at the fourth layer of the Open Systems Interconnection (OSI) model and can handle millions of requests per second. A NLB can not be deployed across regions and would not allow for the correct routing to the API endpoint that will provide the most performant response. So this is obviously a distractor and we can eliminate this answer.
        
        Answer D recommends deploying a Gateway Load Balancer (GLB) in front of the APIs to increase performance. A GLB operates at the third layer of the Open Systems Interconnection (OSI) model, the network layer. A GLB listens for all IP packets across all ports and forwards traffic to the target group that's specified in the listener rule. A GLB can not be deployed across regions and would not allow for the correct routing of the DNS requests to the API endpoint that will provide the most performant response. So again this answer is a distractor and we can eliminate this answer.
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        Great job!
        
    - Walk through Question 2
        
        Hi and welcome back to our second walk through question.  Let’s dive in and read the question.
        
        A company developed an application that is running on a fleet of EC2 instances in an EC2 Auto Scaling Group. The company is currently providing access to the application's API to other AWS accounts via the public internet. After a security audit, it has been determined that access to the API must be private, without exposing the traffic to the internet.
        
        The network engineer has already created a target group listening on the application's port and registered the EC2 instances. The network engineer in the company is worried that other accounts may have an overlapping IP space.
        
        What are the steps that will now need to be taken to satisfy the connectivity and security requirements? (Choose one)
        
        So for this question, what key words and phrases can you identify? The question is asking what steps are needed to change the API from public to private (security requirement) and also ensuring no overlap in IPs (connectivity requirement).
        
        So now let's look at the answers:
        
        A is to configure an Application Load Balancer (ALB) in the company account. Associate the target group with the newly created ALB. Create an endpoint service choosing the ALB and the default configuration. Grant permissions to the other accounts to connect to the endpoint service. The other accounts create an interface endpoint to the service. The company account must accept the connection request.
        
        B is to configure a Network Load Balancer (NLB) in the company account. Associate the target group with the newly created NLB. Create an endpoint service choosing the NLB and the default configuration. Grant permissions to the other accounts to connect to the endpoint service. The other accounts create an interface endpoint to the service. The company account must accept the connection request.
        
        C is to configure an Application Load Balancer (ALB) in the company account. Associate the target group with the newly created ALB. Create VPC peering connections between the company VPC and the other accounts VPCs. The other accounts create a gateway endpoint to the service and modify the VPCs route tables to point to the gateway endpoint.
        
        D is to configure a Network Load Balancer (NLB) in the company account. Associate the target group with the newly created NLB. Create an endpoint service choosing the NLB and the default configuration. Grant permissions to the other account to connect to the endpoint service. The other accounts create an interface endpoint to the service and modify the VPCs route tables to point to the service endpoint.
        
        Were you able to identify any key words or phrases while reading through the answers? Let’s dive deeper into each one and see why the best choice answer is the best choice.
        
        So answer A is Incorrect. Using an Application Load Balancer (ALB) with a VPC endpoint service is an unsupported configuration. So we can identify this as a distractor. Just FYI, you can create a VPC endpoint service for interface endpoints, which requires a Network Load Balancer (NLB), or a VPC endpoint service for Gateway Load Balancer endpoints, which requires a Gateway Load Balancer (GWLB).
        
        Answer B is Correct. You can create a VPC endpoint service for interface endpoints, which requires a Network Load Balancer (NLB). After you create an endpoint service configuration, you must add permissions to enable service consumers to create interface endpoints to your service. With the default configuration, requests from service consumers must be accepted.
        
        Answer C is Incorrect. Using an Application Load Balancer (ALB) with a VPC endpoint service is an unsupported configuration. Again, this is a distractor. You can create a VPC endpoint service for interface endpoints, which requires a Network Load Balancer (NLB), or a VPC endpoint service for Gateway Load Balancer endpoints, which requires a Gateway Load Balancer (GWLB). You cannot create a VPC peering connection between VPCs that have matching or overlapping IPv4 or IPv6 CIDR blocks.
        
        Answer D is Incorrect. After you create an interface endpoint, an endpoint network interface is created and is assigned a private IP address; this private IP address (or, alternatively, the DNS host name) is used to access the service. Since we have identified two distractors (answers A and C), we dive deeper into this answer to see if it would be a better choice than Answer B. Notice there is no mention of a load balancer for this answer and a load balancer is needed because the question mentioned a target group listening on the application's port and registered the EC2 instances. So, we can also identify this one as incorrect and choose Answer B as our best choice answers.
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        How did you answer this question? Did you get it right the first time. Does the correct answer make more sense after we dove into each answer? Did you identify areas that you need more depth?
        
        Great job!
        
- **Module 2: Network Implementation**
    - Domain 2 Introduction
        
        Welcome back. Let's dive into domain two, covering network implementation. 26 percent of the exam content focuses on network implementation. So you can expect about 17 questions. This domain applies the knowledge of network design principles we discussed in the previous domain to address the actual implementation in routing and connectivity between on premises network and AWS using services such as AWS Direct Connect, AWS Site-to-Site VPN, and Transit Gateway.
        
        For domain two, you must also understand how to implement complex DNS architectures using Route 53 hosted zones, sub-domain delegation and conditional forwarding. Exam tip, you can also expect to see some questions around automating the configuration of network infrastructure using services like AWS Cloud Formation here as well.
        
        The second domain network implementation is broken into four task statements. The first task statement is implement routing and connectivity between on premises networks and the AWS Cloud. The second task statement is implementing routing and connectivity across multiple AWS accounts, regions, and VPCs to support different connectivity patterns. The third task statement is implement complex hybrid and multi-account DNS architectures and the fourth task statement is automate and configure network infrastructure.
        
        Over the next several videos in this module, I will address each task statement individually breaking down the knowledge and skills expected of you to be successful. Let's get started with the first task statement covering network implementation and start to evaluate your readiness for the exam in the next video.
        
        **Routing and connectivity hybrid**
        
        Welcome back! Let's begin with the first statement task from Domain 2 which is to implement routing and connectivity between on-premises networks and the AWS Cloud.
        
        This exam tests your ability not only to design, which we covered in Module 1, but to also implement networks in AWS. From the initial design to implementation of your network, security, and compliance are critical to ensure your network connects securely to your AWS environment, remote services, hybrid interconnects, but also on top of your AWS networking services. You will dive deeper into network security in Domain 4, as well as compliance, and governance, but as you may see, topics like security are repeated throughout all domains in the exam guide.
        
        From the exam guide, this task statement has twelve topics you need to understand. Connectivity is a big part of this exam, so make sure you focus on the available hybrid network-connectivity options, but don't skip inter-VPC connectivity options, which we'll dive deeper into in the next lesson. Many organizations adopt a hybrid network architecture with AWS to provide agility, flexibility, scale, and performance while running legacy applications in their on-premise data center in order to optimize connectivity.
        
        How do you migrate applications to AWS and confidently scale your network using the AWS global infrastructure? Consider the additional physical network requirements needed for your hybrid connectivity. Do you use static or dynamic routing protocols? And if so, which ones? What is your implementation plan for fault tolerance and low latency? AWS offers Amazon VPC which provides multiple network connectivity options depending on your network's designs and requirements.
        
        You have options to provision AWS managed VPN to move workloads securely over the internet, to deploy private circuit connectivity with AWS Direct Connect, or the option to enable third-party networking software in your VPC for VPN connectivity. We mentioned this in the Domain 1, but it's important to know what type of hardware do you use to set up Direct Connect. What are the steps needed to set up Direct Connect? Dive deeper into Layer 1 and the types of hardware needed at the co-location facilities.
        
        At Layer 2 and Layer 3, what is the implementation of your routes, switches, gateways, and VLANs? You may also choose a client VPN that allows users to directly access AWS from their desktop or mobile devices.
        
        What is your configuration and implementation for DNS resolution remotely in AWS? Can you implement conditional forwarding? Can you configure resolvers and the needed hosted zones? And for scalability, you need to analyze the connectivity options in relation to the targeted solution scale. What are the influencing factors that are needed when designing and configuring a hybrid connectivity architecture?
        
        Let's also talk about uses cases.
        
        Do you understand the use cases for hybrid connectivity? What are the requirements, is it higher bandwidth, consistent network performance, or increased privacy?
        
        How would you implement a requirement for applications hosted on EC2 instances to increase the connection bandwidth, allow more bytes of data, and increase the payload size per packet between an on-premises data center and a VPC using a virtual private interface?
        
        You could enable the Jumbo MTU option in the private virtual interface, verify that the EC2 instances support jumbo frames, and configure the network MTU setting for each instance to 9001. What is your recommended design and implementation for traffic management if you have very little knowledge of actual requirements?
        
        Here is a hint, dive deeper into Transit Gateway Connect.
        
        Here are more questions to consider:
        
        How would you implement requirements for a customer with a single transit gateway that has multiple VPC and VPN attachments and a Direct Connect connection through Direct Connect Gateway?
        
        Could you associate multiple transit gateways in the same region or connect multiple VPCs in the same or different AWS accounts using the Direct Connect connection?
        
        Many AWS customers rely on VPNs to provide private connectivity between their infrastructure in AWS and on-premises resources, but depending on the requirements, maybe public or private Direct Connect connection is a better choice. Security should always be part of your design.
        
        What security appliance do you implement? How would you update and implement new requirements to comply with new strict security policies to closely monitor the traffic flows on all EC2 instances across different VPCs, perform deep packet inspection, including checking the headers and data on every incoming network packet, and block malicious payloads?
        
        Would you set up VPC traffic mirroring to inspect all network traffic and block malicious payloads or set up a separate Security VPC and enable the AWS Network Firewall to filter the traffic and perform deep packet inspections?
        
        In the first module, Domain 1, we mentioned load balancing which also features in Domain 2. Ensure you can choose and implement the best load balancing solution. Which load balancer can be used as a reverse proxy? Which load balancer operates at Layer 3?
        
        Domain 1 also covered configuring network monitoring and logging in AWS for added visibility. What AWS services can you implement to ensure you have the correct visibility but also that your visibility is automated? An AWS service that may help analyze your global network is Route Analyzer.
        
        Dive deeper and ensure you know what route tables are analyzed with this service.
        
        Will this service validate your existing configurations or verify the route table configuration before sending traffic? How do you diagnose route-related issues or disruptions? And finally, how do you use automation to deploy advanced AWS network solutions without manually configuring each component?
        
        We will dive deeper into automation in the next few lessons, but ensure you understand how to use logging and monitoring to test connectivity. Also dive deeper into AWS Organizations and AWS Resource Access Manager.
        
        Understand how multi-account deployments work for AWS services such as Amazon VPC, transit gateway, Direct Connect, and Route 53.
        
        Understand how to implement each of these to optimize routing and connectivity in your hybrid design.
        
        There is a lot to understand from this first task statement, and some of this has already been covered in the first domain. However, implementing dives deeper than designing, so ensure you dive deep too. You may start to notice that we are talking about the services again and again but relating those to different tasks.
        
        Routing and connectivity are a big part of this exam, and we'll continue to dive deeper in future lessons. Up next, task statement 2.2 on connectivity patterns.
        
        Also, you can scan QR code for the Exam Guide to follow along.
        
        Let's get started with the second statement task from the Network Implementation Domain. And I'll see you in the next video.
        
    - Connectivity patterns
        
        Welcome back. We'll now cover the second task statement from Domain 2, Network Implementation.
        
        Task Statement 2.2 is focused on how to implement routing and connectivity across multiple AWS accounts, Regions, and VPCs to support different connectivity patterns.
        
        This task statement does have topics and knowledge areas that we need to understand. AWS offers design patterns to connect and integrate multiple VPCs into a larger virtual network.
        
        In the last lesson, the focus for that task statement was hybrid network connectivity options, but for this task statement, the focus is inter-VPC connectivity options. Connecting multiple Amazon VPCs at scale could require operational efficiencies, such as a hub-and-spoke network design using VPN, VPC, or transit gateway.
        
        Workloads often exist in multiple environment, these include multi-account, multi-Region multi-cloud environments, both publicly accessible and private, and possibly your existing data center infrastructure. Plans must include network considerations such as intra- and inter-system connectivity, public IP address management, private IP address management, and domain name resolution. Implementing VPC connectivity between VPCs works best without overlapping IP ranges for the VPCs being connected.
        
        As your adoption of multi account strategy grows, cross account networking is needed, as well as a design and configuration to extend to multi-Regions for applications, and disaster recovery too. Let's dive deeper into the second task statement for Domain 2, delivering predictable performance with higher bandwidth and lower latency for use cases such as high performing application access across multiple AWS accounts, Amazon VPCs, and Regions is part of most network designs. For this exam, you should also know how to manage and configure your IT resources in both public and private subnets, and you will most likely see questions on the exam asking you to choose the best answer to connect to Amazon S3 without using an internet gateway or Network Address Translation.
        
        How would you implement a new security requirement for an application running on multiple EC2 instances to allow only those instances from the private subnet access to the new S3 bucket? What if this design already has in S3 VPC endpoint with the default policy and does not have an attached net gateway? Would you modify the bucket policy for your S3 bucket to include the VPC endpoint identifier in the aws:sourceVpce, or edit the VPC endpoint policy to restrict access to the specific S3 bucket only?
        
        And as always, part of the design and implementation must include configuring network monitoring and logging, methods to automate connectivity, and test connectivity too. We've already mentioned AWS services that can help such as Route Analyzer, VPC Reachability Analyzer, and others too.
        
        This task statement also touches on how to expand your AWS deployment and network connectivity, specifically with AWS Organizations and AWS Resource Access Manager. How does sharing your VPCs leverage the implicit routing within a VPC for applications that have a requirement for interconnectivity with the same trust boundaries? Do you know?
        
        Make sure you understand how interconnecting with the right mechanisms can simplify network topologies, and know which connectivity features to use for your requirements, such as PrivateLink, transit gateways, and VPC peering.
        
        What about life cycle management? There could be multiple environments that need to isolate access, but also share resources. How do you configure and connect this environment? When you configure your workloads to communicate between accounts in a shared VPC, do you know which AWS services to use to meet different requirements and use cases? Understand and know how to combine connectivity methods to match the needs of your business.
        
        A variety of connectivity options exist for your Amazon VPC. You can connect your VPC to the internet, to your data center, or other VPCs. The correct answer for you will be based on the AWS resources that you want to expose publicly, and those you want to keep private, and do not forget about authentication and authorization.
        
        There are scenarios to know for multi-Region connectivity between VPCs, for example, how do you scale VPC to VPC connectivity? The simplest way to connect two VPCs is using VPC peering, but this is difficult to manage and scale for larger environments. Transit gateway is easier to manage and scale because AWS manages that high availability and scalability.
        
        As you build your resources in a single VPC and your environment expands to multiple VPCs, greater segmentation and the need to monitor and manage permissions, cost and services grow. How do you configure network connectivity in a single VPC or multi VPC design?
        
        Dive deeper into VPC peering, transit gateway, and PrivateLink, and ask, "Are there existing third party solutions that can help?" When would you choose PrivateLink, transit gateway, VPN, third-party vendors, SD-WAN, over each other? We just mentioned that for smaller scale environments, VPC peering, and for larger environments, transit gateway. Transit gateway adds flexible routing policies and the ability to insert a network appliance as a centralized segmentation security point. Dive deep into configuring these connections.
        
        Most architectures contain multiple VPCs which are shared between two or more AWS accounts. Imagine your company has multiple departments, each with their own VPC that are in the same AWS account, but also have VPCs in different AWS accounts too, and you were tasked to peer the VPCs together, so each department can share resources.
        
        How would you configure and implement the peering and resource sharing with transitive peering? How would you configure and implement a VPC peering connection between two VPCs with overlapping CIDRs? How do you implement the solution for a requirement of a gateway or private connection? Does a peering connection with one VPC and two other VPCs prefer the longest prefix match? Dive deeper because you'll wanna know how VPC peering operates with VPC subnet route tables.
        
        Also ensure you understand how to implement security between network boundaries. You will most likely see questions on how to secure your network using security groups, network ACLs, and AWS Network Firewall, but also understand how to protect users from attacks and being routed to fake websites. How would you secure DNS queries from being intercepted?
        
        Again, we mentioned this in Domain 1, but dive deeper into DNSSEC in Route 53 for this, and dive deeper into configuring DNS solutions for hybrid connectivity. How would you satisfy a new requirement for a startup with a primary website and one subdomain? You could configure Route 53 to route traffic for that subdomain, and also to its lower-level subdomains to improve the DNS resolution and management. But what else is needed? Well, you need to create a new hosted zone for the subdomain, and create records for the lower-level subdomains in that new hosted zone.
        
        But how do you configure the authentication and authorization to this design? SAML? Active Directory? IAM? Or can you use the Route 53 console to authorize?
        
        Up next, we'll dive into task statement 2.3 on DNS.
        
        Follow along with the exam guide and scan the QR code.
        
        Let's get started with the third statement task for Domain 2, network implementation, and I'll see you in the next video.
        
    - DNS
        
        Welcome back. Let's dive into the third task statement from domain two, implement complex hybrid and multi-account DNS architectures. This task statement does have topics and knowledge areas that we need to know and understand. Let's dive in.
        
        A successful hybrid networking strategy goes beyond private network connectivity. It often requires configuring independent internal zones both in your Amazon VPC and on-premise. This type of design needs DNS naming that spans the entire network. Typically, this is managed by providing name resolution services in the same place that the resources and workloads are located.
        
        For example, this happens in places such as an on-premises DNS infrastructure that answers queries for on-premises resources, but this also happens in Amazon Route 53 Private DNS Resolver that answers queries for resources in AWS.
        
        How would you set up Route 53 for a website built on multiple EC2 instances and an application load balancer to access a public domain name and also access its root domain name? Would you set up an alias A record, a non-alias record, or a CNAME record with the application load balancer as the target? How would you update this website design with new requirements to ensure employees do not have to traverse the public internet? To get the unified view of DNS across hybrid networks that your application require, you might need bidirectional query forwarding. This gives you the ability to query your on-premises internal zones from within your Amazon VPC, but it also gives you the ability to query Route 53 Resolver Private DNS from on-premises data centers.
        
        Here's another question. How do you design and configure a Direct Connect connection to allow your on-premises network to access resources in your VPC using a private virtual interface and a custom domain name instead of using the private IPv4 address or private host names provided by AWS? Would you use a private or public hosted zone or maybe conditional forwarding? Do you also need to set up a host condition to route traffic?
        
        For the exam, you also need to know methods to alter your traffic management. If your application is hosted in multiple regions and the requirement is to provide the users with the lowest latency, which Route 53 routing policy do you use? Latency, geolocation, weighted, or multi-value? How is your dev security in Route 53 and DNS? How do you secure the traffic for an application hosted in EKS that uses KMS to secure its data? Well, of course, we wanna ensure the traffic does not use the public internet. Is it possible to connect directly to KMS using a private endpoint in your VPC? If so, for this design, what can you use to log and monitor the traffic? Could you use AWS CloudTrail logs to audit the use of KMS keys through the VPC endpoint? Also, could you use conditions in your IAM and key policies to deny access to any request that does not come from a specified VPC or VPC endpoint?
        
        Here's another question to consider for DNSSEC. How do you configure Route 53 with certificates from AWS Certificate Manager? If an application load balancer is part of the design, could you set up a listener with a host condition to route the zone apex and subdomains to the appropriate target groups?
        
        This task statement covers implementing complex hybrid and multi-account DNS architectures, as well as monitoring, logging, and securing with different scenarios and requirements. Make sure you have a solid understanding of DNS, Route 53, and how to secure your connections. Up next, we'll dive into task statement 2.4 on automation.
        
        Follow along in the exam guide and scan the QR code.
        
        Let's get started with the fourth task statement from domain two, network implementation, and I'll see you in the next video.
        
        **Automation**
        
        Welcome back. Let's dive into the fourth and last task statement from Domain 2 to Automate and configure network infrastructure. This task statement covers the services needed to automate the monitoring, deployment and management of your network and AWS.
        
        We have mentioned scalability multiple times in this course. Automation can help scale changes to the network design and configurations easier than repeatedly requiring human efforts. Infrastructure is code more specifically for this exam.
        
        Network is code creates reusable network infrastructure that is programmable, repeatable, testable version, stored in a source control system and deployed using a continuous delivery pipeline. Ensure you have depth on network and infrastructure as code, the benefits and how automating the process can optimize your network operations.
        
        Automation helps to eliminate risk and achieve efficiency in your network while maintaining the lowest possible cost. Do you have the ability to design and implement automation with your compute and network resources efficiently to meet system requirements?
        
        What about management? How do you maintain the efficiency of your network as demand changes and technologies evolve? Here's a hint that can help dive into the AWS well architected framework performance pillar. Let's dive deeper and cover integrating hybrid network automation options with AWS infrastructure as code.
        
        For the exam, know how to integrate event driven networking functions.
        
        Using CloudFormation, you can create a template of your VPC to facilitate the IP address allocation. In this design, what other AWS service can you use to request a cider block and dynamically look up AMI during the stack creation? AWS systems manager, Lambda, Amazon VPC, IP address management.
        
        If you choose Lambda as your answer, when is that Lambda function in the CloudFormation template invoked?
        
        What if you need a solution to automatically validate that all elastic IP addresses are associated to EC2 instances, or that the elastic IP addresses are being associated to the elastic network interfaces? What AWS service could you use for both?
        
        AWS firewall managers, AWS config, AWS shield, or maybe AWS systems manager?
        
        How would you automate the VPC peering process for newly created VPCs to a shared VPC for a company that has multiple VPCs for each team?
        
        What could be the causes of a CloudFormation error, a VPC peering connection failed to stabilize? In the template, do you check the AWS EC2 route? The peer role ARN, the AWS EC2 VPC peering connection? How can you use automation in AWS to mitigate security threats to your application? What if that application's load balancer is receiving hundreds of random IP addresses and the performance is degrading?
        
        We mentioned this earlier but do you know how to integrate AWS WAF with your application load balancer and configure IP match conditions to block the malicious IP addresses? Or would you use security groups and network access control list? Can you establish a private connection between your VPC and AWS confirmation by creating an interface VPC endpoint and what powers interface VPC endpoints?
        
        For the exam, also understand when to use hard coded instructions in your templates to provision your network resources and also when not to. What complexity does using hard coded templates add? What does AWS recommend instead of hard coding to your templates? Cross stack references, stack sets, modules, parameters.
        
        Other questions to consider for the exam are, what is a use case for exporting resources from your template? What function exports resources? What is the purpose of CloudFormation change sets? And how can you use, IAM with CloudFormation?
        
        Earlier we mentioned the continuous delivery pipeline. How can you implement a continuous delivery system for your CloudFormation templates using AWS code pipeline? You can also use automation in your network monitoring.
        
        CloudWatch provides a dashboard to add visibility but CloudWatch metrics can also be used to create alarms. Understand how to integrate and configure other AWS services such as SNS, Lambda, SQS to help alarm and automatically take actions in your network. Also know where to store your CloudWatch logs and how to filter those logs.
        
        And this wraps up Domain 2: Network Implementation. You can also visit the exam guide by scanning the QR code. Up next, you can engage in a practice activity and after that exercise we'll get started with an introduction to Domain 3: Network Management and Operations.
        
    - Walk through Question 3
        
        Hi and welcome back, let's dive into another walk through question. These walk through questions are meant to assist you in a few ways and will give you an opportunity to see the types of questions you should expect to see in the exam. These questions are not pulled directly from the certification exam, but they are similar to the types of questions on the actual certification exam and will give you opportunities to explore this style of questioning. You will also get to work through methods to help you select the best choice answer, especially for AWS multiple-choice questions. These walk through questions are meant to help you learn how to identify keywords and phrases and also to quickly identify distractors, again so you can choose the best choice answer for each question. Practice exams are great to help you identify the areas you are confident in and reinforce your knowledge, but they can also help you to identify gaps in your knowledge.
        
        As we walk through each of these questions, we will start by reading the question, then we will identify keywords and phrases, and then do the same for each answer. Feel free to pause the video and see if you can identify the correct response yourself. After you have chosen your choice answer, we will walk through each answer and talk about why they are correct or incorrect.
        
        Let’s dive into our third question.
        
        A company provisions an AWS Direct Connect connection to permit access to Amazon EC2 resources in several VPCs and to data that the company stores in private Amazon S3 buckets. The company needs to configure an on-premises router for this Direct Connect connection.  Which solution will require the LEAST amount of operational overhead for the customer router?
        
        What key words and phrases can you identify? How about configure on premises router, several VPCs and also private S3 buckets? The question is asking for a solution to connect the on premises router to the Direct Connect connection with the least amount of overhead.
        
        So now let's look at the answers:
        
        A is Configure several private VIFs. Connect one private VIF to each VPC and one private VIF to the S3 service endpoint.
        
        B is Configure several private VIFs. Connect one private VIF to each VPC. Configure a public VIF for Amazon S3.
        
        C is Configure a private VIF for a Direct Connect gateway. Connect the Direct Connect gateway to each VPC and to the S3 service endpoint.
        
        D is Configure a private VIF for a Direct Connect gateway. Connect the Direct Connect gateway to each VPC. Configure a public VIF for Amazon S3.
        
        Now let's dive deeper into each answer and discuss
        
        So answer A is incorrect and recommends to configure several private VIFs. First, connect one private VIF to each VPC, and then connect one private VIF to the S3 service endpoint. This is incorrect because a private VIF makes Direct Connect connections to VPCs possible. A private VIF connection to Amazon S3 is not possible. So we can go ahead and eliminate this answer.
        
        Answer B is incorrect and recommends to configure several private VIFs and a public VIF. First , connect one private VIF to each VPC, and then configure a public VIF for Amazon S3. This answer is a valid solution, but it is not the best choice answer and is incorrect because it would require additional overhead. A private VIF makes Direct Connect connections to VPCs and Direct Connect gateways possible. A public VIF makes it possible for the Direct Connect connection to connect to public AWS services like Amazon S3. However, many VPC connections over many private VIFs would incur additional operational overhead. A solution that requires less operational overhead would connect to the Direct Connect gateway first and then associate the gateway with the VPC.
        
        Answer C is incorrect and recommends to configure a private VIF for a Direct Connect gateway. So the implementation would be to connect the Direct Connect gateway to each VPC and to the S3 service endpoint. This is incorrect because a private VIF makes Direct Connect connections to VPCs and Direct Connect gateways possible. You can connect a Direct Connect gateway to one or more VPCs. However, a Direct Connect gateway connection to Amazon S3 is not possible. So, again we can eliminate this answer.
        
        Answer D is Correct and recommends to configure a private VIF for a Direct Connect gateway. Here you would connect the Direct Connect gateway to each VPC, and then configure a public VIF for Amazon S3. This answer is the best choice answer from all of the options you were given because the design is doable and it requires the least amount of overhead. A private VIF makes Direct Connect connections to VPCs and Direct Connect gateways possible. A public VIF makes it possible for Direct Connect to connect to public AWS services like Amazon S3. From the other answers, you know that a solution that connects to the Direct Connect gateway first and then associates the gateway with the VPC would require the least amount of operational overhead.
        
        How did you answer this question? Did you get it right the first time. Does the correct answer make more sense after we dove into each answer? Did you identify areas that you need more depth?
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        Great job!
        
    - Walk through Question 4
        
        Hi and welcome back to our fourth walk through question.  Let’s dive in and read the question.
        
        A company is deploying a multi-Regional application to AWS. The company will host the application on Amazon EC2 instances that the company will deploy in several peered VPCs across multiple AWS accounts and multiple AWS Regions. A network engineer must design a DNS solution that would allow all EC2 instances to communicate privately across all VPCs. The design needs to provide multi-Regional resiliency.
        
        Which of the following designs should the network engineer implement?
        
        So for this question, what key words and phrases can you identify? How about multi-Region, multi-account, peered VPCs, and private connectivity/communication. The question is asking which design should the engineer implement to provide a DNS solution that allows all EC2 instances to privately communicate across all VPCs, and the design must add multi-Regional resiliency.
        
        So now let's look at the answers:
        
        A is to Retain the DNS service on premises. Connect the VPCs to the on-premise location by using an AWS Site-to-Site VPN. Create an Amazon Route 53 Resolver and register all the EC2 instances with the on-premises DNS to make resolution possible.
        
        B is to Create a private hosted zone in Amazon Route 53. Associate all the VPCs with the private hosted zone. In all accounts, authorize the hosted zone associations. Create Route 53 resource record sets for the EC2 instances in the VPCs.
        
        C is to Attach all the existing VPCs to a newly created transit gateway in each Region. Peer the transit gateways in each Region to each other. Create a central transit gateway route to allow all the EC2 instances to communicate.
        
        D is to Deploy the EC2 instances to public subnets with auto-assigned public IPs. Register a new domain and create a public hosted zone in Amazon Route 53. Run an AWS CLI script at startup to register each EC2 instance with the new domain.
        
        Let’s dive deeper into each answer and see why the best choice answer is the best choice.
        
        So answer A is Incorrect and recommends to retain the DNS service on premises. For this implementation, you would connect the VPCs to the on premises location by using an AWS Site-to-Site VPN. Then you would create an Amazon Route 53 Resolver and register all the EC2 instances with the on-premises DNS to make resolution possible. This answer could be tricky because it is partially correct. You can configure Route 53 inbound and outbound endpoints to answer DNS queries to and from your on-premises environment by configuring forwarding rules for specific domain names. However, Route 53 resolvers are Regional resources that would not ensure multi-Regional resiliency.
        
        Answer B is Correct and recommends to create a private hosted zone in Amazon Route 53. First you would associate all the VPCs with the private hosted zone. Then in all accounts, authorize the hosted zone associations. And finally, create Route 53 resource record sets for the EC2 instances in the VPCs. This DNS solution would allow all EC2 instances to communicate privately across all VPCs, and it would also provide multi-Regional resiliency. A private hosted zone is a container that holds information about how Route 53 responds to DNS queries for a domain and its subdomains within one or more VPCs across one or many accounts. Other accounts must authorize all cross-account associations. Once the private hosted zone is established, resource records can be created and resolved across the VPCs.
        
        Answer C is Incorrect and recommends to attach all the existing VPCs to a newly created transit gateway in each Region. For this design, you would first peer the transit gateways in each Region to each other, and then create a central transit gateway route to allow all the EC2 instances to communicate. This is incorrect because a transit gateway allows users to attach VPCs in the same Region and route traffic between them. You can peer transit gateways across Regions. However, in this scenario, the company has already peered the VPCs. The transit gateway would not meet the requirement for cross-VPC DNS resolution.
        
        Answer D is Incorrect and recommends to deploy the EC2 instances to public subnets with auto-assigned public IPs. For this solution, first you would register a new domain and create a public hosted zone in Amazon Route 53. Next you would run an AWS CLI script at startup to register each EC2 instance with the new domain. We know that a public hosted zone is a container that holds information about resolution and routing traffic on the internet for a specific public domain. And remember that the company wants to make private address resolution possible. So this solution to use a public hosted zone would make the application public.
        
        How did you answer this question? Did you get it right the first time. Does the correct answer make more sense after we dove into each answer? Did you identify areas that you need more depth?
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        Great job!
        
- **Module 3: Network Management and Operation**
    - Domain 3 Introduction
        
        Welcome back. Let's dive into domain three, which is network management and operations. This domain covers 20% of the exam content, so you can expect about 13 questions involving network management and operations.
        
        This domain is broken into three task statements. The first task statement is maintain routing and connectivity on AWS and hybrid networks. The second task statement is to monitor and analyze network traffic to troubleshoot and optimize connectivity patterns. And the third task statement is to optimize AWS networks for performance, reliability, and cost effectiveness. In this domain, you will apply your knowledge of network design and implementation to manage your network and environment to ensure not only performance efficiency but operational excellence.
        
        Management and operations in AWS is not a choice between innovations and control because AWS helps to implement and operate dynamic, centrally-managed, secure, multi-account networks and environments.
        
        Provisioning and orchestration in AWS entails building and sharing resources in a consistent and repeatable process to scale as needed, and this includes our network configurations and connectivity. Let's dive deeper to understand how to define and configure VPC subnets and manage routing protocols over hybrid connections.
        
        This domain and its task statements will help to ensure you understand how to define and configure route tables to direct network traffic while managing public and private access to AWS services. On the exam, you may be asked to choose the appropriate network configuration to reach a performance goal or to reduce cost.
        
        In a previous lesson, we mentioned that the optimal network solution is based on latency, throughput requirements, jitter and bandwidth. Physical constraints such as where your users are located or connections to your on-premises resources should also be included in your requirements for that optimal design. Management and operations requires that you have the needed visibility and are tracking the correct metrics.
        
        You have to design your network so it provides the necessary information to understand its internal state across all components to support observability. Using metrics, logs, events and traces can record system events in your network and quickly identify, resolve and remediate any issues. Expect to see a few questions that require you to identify a network issue by analyzing a VPC flow log or a CloudWatch log.
        
        Flow logs specifically help to diagnose restrictive security groups, monitor traffic, and show the direction of traffic across your network interfaces. VPC flow logs are easy to implement, but VPC traffic mirroring gives you a lot more context to analyze.
        
        You should also understand the purpose of VPC traffic mirroring and its associated use cases. Copying network traffic from the elastic network interfaces adds network based monitoring and analysis because it captures raw packet data needed for content inspection.
        
        Use cases are network security, network performance monitoring, management and troubleshooting. You have to understand and choose the AWS service to collect the metrics and logs to ensure high availability, performance and reliability. Monitoring the metrics and adding observability ensures you can troubleshoot quicker.
        
        Another part of management and operations is optimizing over time. Once your network and workloads are implemented and you've begun logging the appropriate metrics, you must monitor the network performance to ensure you are tracking the correct metrics to remediate any issues before they impact your customers.
        
        But monitoring metrics should be used to raise alarm when thresholds are breached. You can use AWS services and their metrics to assess their resource utilization and identify ways to reduce costs and maintain and optimize network with performance efficiency and operational excellence.
        
        And remember to stay current on all the new services, features, tools, and so on.
        
        Over the next several videos in this module, I will address each test statement individually, breaking down the knowledge and skills expected of you to be successful.
        
        Let's get started with the first test statement covering network management and operations, and start to evaluate your readiness for the exam in the next video.
        
    - Routing and connectivity optimization
        
        Welcome back, let's begin with the first task statement from domain three which is to maintain routing and connectivity on AWS and hybrid networks.
        
        This exam tests your ability not only to design and implement but also know how to manage optimized networks in AWS. The careful planning and management of your network design forms a foundation of how you provide isolation and resource boundaries and network connectivity. Your network strategy for operational excellence requires network design and configurations that can be reusable in scale but should also align to your security architecture. In previous lessons, we talked about how automation can help to enforce the use of non-overlapping private subnets when provisioning new AWS accounts and VPCs. This automation should also define which network controls and patterns to deploy during implementation, as well as updates to ensure you continue to optimize over time.
        
        Since workloads often exist in multiple environments including publicly, accessible, private, and your on premises too, configurations must include intra and interconnectivity, public IP address management, private IP address management, and DNS.
        
        How would you manage and operate your network to ensure the principle of lease privilege is used across your network to access your AWS resources? Implementing a strong identity foundation using the principle of lease privilege, enabling traceability, applying security at all layers, protecting your data in transit and at rest, and preparing for security events are crucial, but do not forget to automate these security best practices to improve your ability to scale securely and cost effectively.
        
        A reliable network depends on communications for connectivity, but also interconnecting components such as services, instances, and servers. How do you decide which regions to include or exclude in deployments, also needs to include the connectivity to ensure reliable operations with no data loss or latency.
        
        For the exam, make sure you know the available inter-regional and intra-regional communication patterns. Do you know if all of your Amazon VPCs, site to site VPN connections and Direct Connect gateways attached to an AWS transit gateway hosted in an AWS region can exchange traffic with resources deployed in other AWS regions?
        
        Absolutely, inter region peering capability simplifies routing and interconnectivity between your VPCs and on premises network. Remember, Direct Connect gateways are global and you can configure multiple transit gateways for routing between different traffic gateways in the same region and different regions too.
        
        Also understand how inter region traffic can reduce the attack service. Load balancers only accept traffic on its listeners and support proxy connections to your resources ensuring only well formed TCP connections result in your data flow.
        
        But what are other ways to maintain private access for your traffic and services and maintain connectivity? Dive deeper into your subnets, route tables, security groups, network, ACLs, ports and protocols.
        
        For this task statement you also need to have an understanding of how to manage connections to load balancers, CloudFront, Route 53 and API gateways, as well as Direct Connect gateways, transit gateway, and virtual interfaces.
        
        Can you design, implement, and manage the industry standard routing protocols that are used in most hybrid networks? For example, BGP over Direct Connect or connectivity options for Direct Connect connection or a VPN.
        
        What type of virtual interface would you create if you needed to establish a Direct Connect connection to your on-premises network for accounts in your AWS organizations? But the virtual interface needs to be owned by a different AWS account than the account owning the Direct Connect connection. Public, private, transit or hosted?
        
        The answer is a hosted virtual interface for the other account. This exam requires you to understand and manage connections. AWS has many different types of route tables to help with the configuration and management, and for this exam take some time to review each type, understand how to use route tables to direct traffic appropriately, here are a few questions and tips to consider.
        
        With a AWS site to site VPN, the type of routing you select will depend on the gateway device. If your virtual private gateway uses path selection and longest prefix match to determine how to route traffic, What is the most preferred route that a virtual private gateway will prioritize?
        
        When your virtual private gateway receives routing information, it uses past selection to determine how to route that traffic. Longest prefix match applies, but if the prefixes are the same what is the most preferred route?
        
        First, BTP propagated routes from an AWS Direct Connect connection. Second, manually added static routes for a site to site VPN connection. Third, BGP propagated routes from a site to site VPN connection. And fourth, specifically for matching prefixes where each site to site VPN connection uses BGP, the AS PATH is compared and the prefix with the shortest AS PATH is preferred.
        
        Here's an exam tip, make sure you know what a virtual private gateway provides for your VPC. Understand how it provides edge routing for AWS managed VPC connections and Direct Connect connections and how it acts as a next hop router managing the edge routing information separate from your VPC route tables.
        
        Another area for this task statement is troubleshooting issues.
        
        We've been talking about monitoring to collect metrics and logs to add visibility and detect and investigate issues, but to ensure operational excellence, reliability, and performance efficiency, we do not want to investigate when issues arise, but monitoring allows us to investigate more quickly, identify root cause, and remediate the issue because we are already correlating our data across metrics, logs and traces.
        
        For this exam, you'll be expected to know and answer troubleshooting questions. Do you know how to troubleshoot a BGP session that is blocking your ability to establish a connection over a Direct Connect link? Do you verify the MTU of the virtual interface is using jumbo frames and set to 9001 or do you verify that BGP peers are not more than one hop from each other? Do you check to see if the virtual private gateway allows EBGP multi hopping?
        
        To perform troubleshooting, check the Direct Connect link status. If it is up, check and verify the configuration on the Direct Connect router. Then ensure the Direct Connect router or any other device is not blocking the ingress and egress from TCP port 179 and other ephemeral ports. BGP ports cannot be more than one hop away from each other because external BGP, EGBP, multi hop is disabled on the AWS side.
        
        What about limits and quotes? Do you know how they affect AWS networking services? Dive deeper into these questions. What are the bandwidth and route limits on different AWS networking services? How many VPCs can you attach to each transit gateway? How much traffic can each attachment handle?
        
        According to the AWS documentation, it's up to 50 gigabits per second of burst of traffic. But back to our optimal network design, it's going to vary based on latency, throughput requirements, jitter and bandwidth. When do you optimize routing over dynamic and static routing protocols?
        
        First, understand how networking impacts performance. Second, choose appropriately sized dedicated connectivity to ensure you have enough bandwidth for the workload performance or use VPN for hybrid workloads. Third, choose network protocols that optimize your traffic. And fourth, optimize the network configuration based on metrics and then continue to use networking metrics to identify changes needed to your network configuration as your network evolves.
        
        Evolving your network architecture over time is necessary to maintain performance efficiency. A common situation that requires management and operation attention is when there are resources with overlapping IP address ranges that must communicate.
        
        What are use cases for summarizing routes inside or overlap? Summarization saves memory, bandwidth, CPU cycles and add stability. CIDR overlap is when two different networks using overlapping or identical IP address ranges have resources that need to communicate.
        
        An example here would be when a VPC with a 10.0.0.0/8 CIDR is peered with a VPC with a 10.0.0.0/16 CIDR. Another common situation we see in customer networks is when there are resources with overlapping IP address ranges that must communicate with each other.
        
        Frequently this occurs when companies are acquired and have used the same private RFC1918 address ranges. However, it can also occur when a service provider with a unique IP range must provide access to two different customers that each have the same IP range. This is usually unintentional and can also occur with third parties such as Docker.
        
        The solution will depend on the requirements for communications. Perhaps you need complete connectivity between two applications, but maybe you only need outbound connectivity where sessions are established from one network to the other and not back ingressing.
        
        Overlapping CIDR's can have additional calls, increased complexity for the connectivity, complex troubleshooting and compatibility issues. Most solutions for overlapping CIDR involve NAT which involves additional management overhead as the overlapping IP address firewall rules and usually requires additional metrics and logs.
        
        For this task statement and exam, ensure you have the ability to identify and manage your networking resources with an understanding of routing, NAT, IP protocols, OSI model as well as the ability to calculate IP address ranges and their characteristics.
        
        Up next will dive into the second task statement 3.2 on troubleshooting and optimizing connectivity.
        
        Scan the QR code for the exam guide to follow along and I'll see you in the next video.
        
    - Troubleshooting
        
        Welcome back. Let's dive into the second task statement for Domain 3, Monitor and analyze network traffic to troubleshoot and optimize connectivity patterns. As you are seeing, AWS provides networking services and features to connect into, AWS outside of AWS, and also hyperconnectivity to your on-premises. AWS also provides services, features, tools, and techniques for troubleshooting network connectivity issues.
        
        In the last lesson, we said that your network strategy for operational excellence requires network design and configurations that can be reusable and scale, but you should also align to your security architecture. But part of your network design must include monitoring, analyzing, and troubleshooting to maintain performance efficiency, and operational excellence.
        
        So what is your troubleshooting approach? Do you follow a bottom up approach, top down approach, or do you follow a combination and adjust your troubleshooting approach based on the issues?
        
        Most engineers know how to traverse the OSI model from layer 1 to layer 7 to identify the issue or issues. In your VPC, AWS adds implicit routing for all of the subnets by default. In this case, what layer of the OSI model do you begin to troubleshoot? Layer 2, 3, or 4.
        
        When you manage services on premises, you need to understand what each device is doing at each layer, but how do you troubleshoot using the OSI model in AWS?
        
        What layer would you begin troubleshooting if your EC2 supports an application and uses a custom route? Probably at layer 7. But in AWS and with virtualization, the OSI layers 3 to 7 become abstracted, and in reality it gives us different layers of control and access. Most is abstracted virtual and exist as code, but we still have layers of control and management when we create multiple AWS accounts, multiple VPCs, and subnets, different applications instances, storage, services, and so on.
        
        On AWS, networking is virtualized and available in different types and configurations. In part of managing and operating an optimal network is not only monitoring the performance, but also having a troubleshooting plan with hopefully automation for resolutions.
        
        We mentioned in the last lesson to know your service limits, and adding visibility with observability to easily identify trouble in your network ACLs or security group configurations. AWS provides services to help with troubleshooting, like AWS Config, CloudWatch, Transit Gateway, Network Manager, Reachability Analyzer, VPC Flow Logs, and VPC Traffic Mirroring.
        
        For this exam, you need to be able to identify performance metrics and reachability constraints in your network to monitor and optimize, and know how to troubleshoot any issues. What AWS service provide to you the ability to collect, analyze, and automate your network performance? CloudWatch is the usual first choice, but we have additional services, features, and tools to dive deeper. How do you diagnose network issues, such as packet loss or high latency?
        
        First, we need to have benchmark for our performance results. Second, check if the instant supports enhance networking. And third, verify you can connect to the instance to ensure there is end to end connectivity. What tools could you use to further troubleshoot? VPC Flow Logs, Traffic Mirroring, VPC Reachability Analyzer, and Network Manager would help with the troubleshooting. Before this exam, we also need to know other tools we could use such as, Traceroute, MTR, TCP dump, and so on.
        
        Once the source of the issue has been identified, check your benchmark to see how does that compare to the current performance issues. How do you identify that the source of the issue is the network or an application? Because as network engineers, we know it's always the network. AWS provides tools to collect and analyze our network metrics and logs, but which tools you use for troubleshooting will depend on the issues in your design. Do you know when you would use a specific tool to collect and analyze your logs and metrics? No one understand when to use CloudWatch, VPC Flow Logs, or Traffic Mirroring.
        
        What tool would you use to analyze your routing patterns and issues? Route Analyzer performs route analysis. What would be the use case to use VPC Reachability Analyzer, or Transit Gateway Network Manager? Reachability Analyzer would be great for troubleshooting connectivity issues, verifying your network configuration, and automating the verification of connectivity as your network configuration changes over time. Network Manager helps to quickly add on premises location respond to connectivity issues, and identify global network issues.
        
        If you have several VPCs connected by a Transit Gateway, what tool do you use to monitor all IP traffic going to and from the network interfaces for all of your EC2 instances? Would you create a custom format with VPC Flow Logs, or use VPC Traffic Mirroring to capture VPC traffic?
        
        Well, VPC Flow Logs captures all IP traffic going to and from your network interfaces. What AWS service would you choose to implement if you need a single global view of your private network that includes your VPC with a Direct Connect connection and a VPN connection to your on-premises network? Would you rely on AWS Transit Gateway, Network Manager, or VPC Reachability Analyzer?
        
        We just mentioned that VPC Reachability Analyzer is better for troubleshooting connectivity issues that are caused by network misconfigurations and also verifies that a network configuration meets network design requirements. Network Manager maps your network topology. How would you design and implement automating the verification of connectivity intent as a network configuration changes to ensure it is correct before the change is applied? VPC Reachability Analyzer or Network Manager? We just mentioned this use case too, it would be VPC Reachability Analyzer.
        
        These services need a deep dive to be able to choose the best choice answer in your exam. Let's dive deeper into using metrics and logs to troubleshoot. Network engineers and network security engineers view traffic as a source of truth, because it provides a view into communications between different entities in the infrastructure. But how do you log that traffic in AWS?
        
        We have mentioned VPC Flow Logs, CloudWatch, VPC Traffic Mirroring, but do you understand what resource to use and what it logs to ensure you are logging the needed information?
        
        VPC Traffic Mirroring can help to apply a deep packet inspection, signature analysis, anomaly detection, and machine learning based techniques to add more security, performance, monitoring, and troubleshooting when visibility beyond what is available through the VPC Flow Logs is needed.
        
        This includes situations where packet traces must be captured in a packet analyzer appliance. And then adding automation to quickly resolve and remediate any issues is crucial in our troubleshooting plan. AWS provides the ability to collect metrics and in conjunction with Amazon CloudWatch, metrics, events, and alarms, to take specific actions when a set threshold is met or exceeded.
        
        How would you troubleshoot an MTU size mismatch between VPC peering and the Transit Gateway during migration from VPC peering to Transit Gateway? And how would you update your design to avoid jumbo packets dropping due to the size mismatch? Transit Gateway metrics can be sent to CloudWatch, but you can also use Transit Gateway Flow logs, VPC Flow Logs, and CloudTrail logs too.
        
        These are things you need to know for this exam. This task statement validates the ability to visualize, monitor, and troubleshoot your network and resources. For the exam, ensure you understand the methodology of troubleshooting, the core concepts for troubleshooting connectivity in AWS, using both traditional tools and AWS tools too, and know scenarios of when to use what.
        
        Up next, we'll dive into the task statement 3.3 for performance reliability and cost effectiveness. Follow along with the exam guide by scanning the QR code and I'll see you in the next video.
        
    - Performance and cost optimization
        
        Welcome back, let's dive into the third task statement from Domain Three, Optimize AWS networks for performance, reliability, and cost-effectiveness. So far in this module, we have discussed that an optimal network is measured by the efficient and effective management of operational events to achieve operational excellence. This applies to performance, reliability, and cost-effectiveness too.
        
        You must understand which metrics and logs to track, how to add visibility using dashboards and notifications to alert, how to troubleshoot, and how to take appropriate action immediately using AWS services. In AWS, you can generate dashboard views of your metrics collected from workloads. AWS provides workload insights through logging capabilities including AWS X-Ray, CloudWatch, CloudTrail, and VPC Flow Logs enabling the identification of workload issues in support of root cause analysis and remediation. Using the data collected helps to select optimized patterns and implementation to then manage and ensure not only a reliable, high-performing, but cost-effective solution.
        
        AWS has multiple services to match your network needs and methods, such as Enhanced Networking, Amazon EBS-optimized instances, S3 transfer accelerator, and CloudFront to optimize network traffic. AWS also offers networking features, Route 53 latency routing, VPC endpoints, Direct Connect, and Global Accelerator to reduce network distance or jitter.
        
        A few questions for the exam to consider are, what are the different approaches you can implement to reduce the bandwidth utilization? Can you control the send rate and limit outgoing bandwidth in exchange for increased latency? We know we can use CloudWatch metrics to monitor instance network bandwidth and the packets sent and received. But we can also use the network performance metrics provided by the Elastic Network Adapter driver to monitor when traffic exceeds the network allowances that Amazon EC2 defines at the instance level. What are other ways to improve your network performance in AWS?
        
        You can use load balancing for offloading encryption termination to improve performance and to manage and route traffic effectively. For different connection types, know what frame size optimization options are available and how each affect bandwidth limits. And use requirements to determine the appropriately sized dedicated connectivity.
        
        Do you need a single VPN connection or multiple connections to load balance across the connections? Maybe instead you need a Direct Connect connection. For this exam, ensure you understand how your network optimization is measured. And dive deeper into using your collected and analyzed data to make informed decisions about optimizing your network configuration. And for continual improvement, measure the impact of those changes for updates and future configurations too.
        
        The network is between all components in your environment. Most applications are built from multiple distributed components that need to communicate. And the number of network devices, endpoints, users, applications, and more that are on your network can have major impacts on your data flow and bandwidth utilization.
        
        And along with that, know how the type of traffic on your network can impact how your network performs. If performance could be better, how do you optimize the traffic? Large files, backups, tasks, and more can slow you network's throughput. What is usually the root cause here? Sometimes it is that older devices do not have the needed bandwidth affecting overall end to end traffic performance, but it could also be that utilization issues with your routers or switches or security appliances add additional latency. For the exam, dive deeper to understand the different types of network interfaces available to optimize your traffic in AWS.
        
        If your application is using a fleet of EC2 instances to process large amounts of data and you have a requirement for low latency and high throughput, what type of network device would you attach to ensure the instances can communicate directly with the network interface hardware? ENA, EFA, or ENI? EFA is the answer.
        
        Let's move on and talk about resilience and reliability. Do you understand the high-availability features of Route 53 and which routing policies include DNS load balancing with health checks, or which record sets would be best? How would you create Route 53 public hosted zones and private hosted zones and records to optimize application availability? Dive deeper into routing policies and their health checks. Could you create a private zonal DNS entry to route traffic to multiple Availability Zones? Yes, but it has to be in the same AWS account.
        
        What routing policy would you implement to ensure an application's resilience and high availability? Simple, Failover, Weighted, or Latency-based? Failover routing ensures high availability and resilience. What else could be implemented to increase network performance for the application? AWS provides Global Accelerator, S3 Transfer Accelerator, endpoints, placement groups, and more.
        
        Make sure you know what the enhanced networking options are for instances in AWS. How do you configure jumbo frames across connection types? Placement groups or a Direct Connect connection can help. Do you know when traffic is limited to a maximum MTU of 1500? Is it, traffic over an internet gateway, traffic over an inter-region VPC peering connection, traffic over VPN connections, traffic outside of a given AWS Region for EC2-Classic, or all of the above? Traffic is limited to a maximum MTU of 1500 for all of the above.
        
        Let's jump into optimizing our subnets and auto scaling. How do you update and optimize subnets for auto scaling configurations? To load balance application traffic at Layer seven, could you deploy a Kubernetes ingress, which provisions an AWS Application Load Balancer? Or would you use an AWS Load Balancer Controller to manage the load balancing of a Kubernetes cluster? If so, what resource does it create when you create a Kubernetes service type of load balancer? By default, it creates an Application Load Balancer, but you can also create a Network Load Balancer.
        
        Since we are talking about AWS services, what AWS service helps to optimize network connectivity to improve network performance and application availability? We have mentioned this one many times throughout this course, it's Global Accelerator. After analyzing a requirement to link two or more VPCs, how do you choose between VPC peering, proxy patterns, or a transit gateway? Following that, how do you implement a design or solution using the appropriate connectivity service to meet set performance goals?
        
        Again, dive into transit gateway, VPC peering, VPN, Direct Connect, and PrivateLink. It's critical for this exam to know when to use each AWS network connectivity service. What about configuring multicast on a transit gateway using the Amazon VPC console or the AWS CLI? Do you first create a multicast domain?
        
        If this is your first step, you need to know if your hosts use the Internet Group Management Protocol for multicast traffic. In AWS, when you have at least one host that uses IGMP protocol for multicast traffic, AWS automatically creates the multicast group when it receives an IGMP JOIN message from an instance. It then adds the instance as a member in this group.
        
        What does that allow? It allows any instances that are in subnets associated with the multicast domain to send traffic, and it also allows the group members to receive the multicast traffic too. Could you answer a question on managing IGMP configurations? There are five best practice areas for cost optimization in AWS, Practice Cloud Financial Management, Expenditure and usage awareness, Cost-effective resources, manage demand and supply resources, and optimize over time.
        
        And for this exam, you must know how to choose hybrid networking connectivity for workloads with varying requirements for throughput and consistency.
        
        Here is a hint for the exam, dive deeper into the cost optimization and the reliability pillar of the AWS Well-Architected Framework. Ensure you understand continual refinement of your network over its entire lifecycle from the proof of concept to the final optimized configurations. There are always tradeoffs to consider when building your network.
        
        Do you optimize for performance and reliability or cost? Ensure you understand how to monitor the usage if your network and identify the correct metrics and benchmarks. Remember to also dive into data transfer costs and storage.
        
        Is it more cost effective to use an VPN connection for non-critical workloads that have no strict resiliency or latency requirements? You may decide to use VPN connections for non-critical traffic but choose private dedicated connectivity for your production traffic ensuring consistent and higher bandwidth.
        
        If you have a small hybrid network with a few VPCs and you are required to quickly establish connectivity, and cost-saving is a top requirement, what would you use? Virtual Private Gateways can terminate your Site-to-Site VPN or private Direct Connect connections, but if you have multiple VPCs and need to have network connectivity to your on premises environment, use a transit gateway in addition to Site-to-Site VPN or Direct Connect.
        
        Do you know why these options would help with your cost optimization? While Transit Gateway scales your VPN and Direct Connect connections and simplifies management, you are charged for the number of connections that you make to the Transit Gateway per hour, and the amount of traffic that is processed by the Transit Gateway.
        
        Do you know how to design and implement to avoid transit gateways data processing fees? Another part of cost optimization is forecasting connectivity demands, because it does take time to establish some connections and you cannot dynamically provision and increase the speed of your Direct Connect connection.
        
        For the exam dive deeper into best practices for designing and operating reliable, secure, efficient, and cost-effective hybrid networks. This task statement covers all concepts needed to monitor, manage, and optimize your network for both performance and cost optimization. Understanding the relationship between your network services, features, tools, metrics, instances, applications, and so on is at the core to improving your performance and reliability. AWS services have features you can use to increase performance, but also test your network, understand your network's baselines and peak capabilities.
        
        Scan the QR code to follow along. Up next, we'll go through a few walk through questions for Domain Three, and I'll see you in the next video.
        
    - Walkthrough Question 5
        
        Hi and welcome back, let's dive into another walk through question. These walk through questions are meant to assist you in a few ways and will give you an opportunity to see the types of questions you should expect to see in the exam. These questions are not pulled directly from the certification exam, but they are similar to the types of questions on the actual certification exam and will give you opportunities to explore this style of questioning. You will also get to work through methods to help you select the best choice answer, especially for AWS multiple-choice questions. These walk through questions are meant to help you learn how to identify keywords and phrases and also to quickly identify distractors, again so you can choose the best choice answer for each question. Practice exams are great to help you identify the areas you are confident in and reinforce your knowledge, but they can also help you to identify gaps in your knowledge.
        
        As we walk through each of these questions, we will start by reading the question, then we will identify keywords and phrases, and then do the same for each answer. Feel free to pause the video and see if you can identify the correct response yourself. After you have chosen your choice answer, we will walk through each answer and talk about why they are correct or incorrect.
        
        Let’s dive into our fifth question.
        
        A Software as a Service (SaaS) provider has deployed their public offering to several private subnets in an Amazon VPC. The company is looking for a solution that would allow them to integrate their platform into their client private networks in VPCs on AWS. The company has employed a network team to propose a solution that can provide the ability for the SaaS platform to integrate with thousands of potential customers, regardless of the customer VPC network configuration.
        
        Which solution should the network team recommend?
        
        So for this question, what key words and phrases can you identify? How about private subnets in a VPC and integrating their platform with the private subnets and VPC. The question is asking which solution would the network engineer recommend from the responses below.
        
        So now let's look at the answers:
        
        A is to create an endpoint service powered by AWS PrivateLink and associate each customer VPC with the newly created endpoint service. Instruct the customers to create an interface VPC endpoint in their accounts to access the SaaS application.
        
        B is to attach an internet gateway to the private subnets in the existing VPCs. Attach Elastic IPs to the SaaS front-end instances. Create Security Group rules that only allow traffic from client VPCs to access the SaaS application.
        
        C is to deploy NAT gateway into the SaaS VPC subnets. Route all the traffic through the NAT gateway to the other client VPCs. Create Security Group rules that only allow traffic from client VPCs to access the SaaS application.
        
        D is to establish VPC peering with each of the customer VPCs. Create a single route to the subnets that host the SaaS front-end instances. Attach the route to all the peering connections to allow access to the SaaS application.
        
        Now let's dive deeper and discuss the why the responses are correct or incorrect.
        
        So, answer A is correct and recommends to create an endpoint service powered by AWS PrivateLink and associate each customer VPC with the newly created endpoint service. Instruct the customers to create an interface VPC endpoint in their accounts to access the SaaS application. AWS PrivateLink is a highly available, scalable technology that enables private connectivity between supported AWS services and 3rd party SaaS providers and VPCs. AWS PrivateLink enables the ability to connect an application to thousands of VPCs even in cases where VPCs are configured with overlapping IPs.
        
        Whilst we’ve talked about the right answer first, just by luck, lets still go through the other answers and talk about why they aren’t a fit
        
        Answer B is incorrect and recommends to attach an internet gateway to the private subnets in the existing VPCs. Attach Elastic IPs to the SaaS front-end instances. Create Security Group rules that only allow traffic from client VPCs to access the SaaS application. Attaching an internet gateway and Elastic IPs would make the application public. This is not the desired configuration and would needlessly expose the application to the public internet.
        
        Answer C is incorrect and recommends to deploy NAT gateway into the SaaS VPC subnets. Route all the traffic through the NAT gateway to the other client VPCs. Create Security Group rules that only allow traffic from client VPCs to access the SaaS application. NAT gateways would not allow external customers to initiate a connection to the SaaS application.
        
        Answer D is incorrect and recommends to establish VPC peering with each of the customer VPCs. Create a single route to the subnets that host the SaaS front-end instances. Attach the route to all the peering connections to allow access to the SaaS application. A VPC peering connection is a networking connection between two VPCs that enables routing of traffic between them using private, non-overlapping IPs. Using VPC peering would not allow for clients to use overlapping IPs in their VPCs and would require coordination of networking configuration between the SaaS provider and clients.
        
        How did you answer this question? Did you get it right the first time. Does the correct answer make more sense after we dove into each answer? Did you identify areas that you need more depth?
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        Great job!
        
    - Walk through Question 6
        
        Hi and welcome back to our sixth walk through question.  Let’s dive in and read the question.
        
        A company has deployed Amazon EC2 instances in private subnets across 20 VPCs in a single AWS Region. The company deployed NAT gateways in each VPC. The instances occasionally download patches from the internet through the NAT gateways. The NAT gateways each process less than 1 GB of data each month. The company recently migrated from using VPC peering to AWS Transit Gateway.
        
        Which solution will reduce costs the MOST?
        
        So for this question, what key words and phrases can you identify? How about instances in private subnets, across 20 VPCs, one Region, and occasionally download patches from the internet using NAT gateways. The question is asking which solution will reduce costs the MOST because VPC peering is free but there is a cost associated with transit gateways. So a key here is understanding the data transfer costs.
        
        So now let's look at the answers:
        
        A is to Redeploy the NAT gateways in their current VPCs. Ensure the NAT gateways are in the same Availability Zones as the instances that generate the most egress traffic.
        
        B is to Delete the existing NAT gateways. Deploy a NAT gateway in a separate egress VPC. Delete the transit gateway and use VPC peering to send internet traffic to the egress VPC.
        
        C is to Configure gateway VPC endpoints in each VPC where the EC2 instances are located. Modify the route tables of the private subnets to send internet traffic through the endpoints.
        
        D is to Delete the existing NAT gateways. Deploy a NAT gateway in a separate egress VPC. Modify the transit gateway route tables to direct internet traffic to the egress VPC.
        
        Let’s dive deeper into each answer and see why the best choice answer is the best choice.
        
        So answer A is Incorrect and recommends to redeploy the NAT gateways in their current VPCs. Ensure the NAT gateways are in the same Availability Zones as the instances that generate the most egress traffic. Data that is transferred across Availability Zones in the same Region incurs a cost in each direction. This solution could be cost-effective if you send a large amount of data through the NAT gateways because this solution would avoid the need to pay extra transit gateway data processing charges. However, in this scenario, only a small amount of data is processed by NAT gateways.
        
        Answer B is incorrect and recommends to delete the existing NAT gateways. Deploy a NAT gateway in a separate egress VPC. Delete the transit gateway and use VPC peering to send internet traffic to the egress VPC. You could reduce costs by deleting the existing NAT gateways and deploying a NAT gateway in an egress VPC. However, you cannot route traffic to a NAT gateway through a VPC peering connection.
        
        Answer C is Incorrect and recommends to configure gateway VPC endpoints in each VPC where the EC2 instances are located. Modify the route tables of the private subnets to send internet traffic through the endpoints. This solution could be a valid approach if you host the patches in Amazon S3. You could configure a gateway VPC endpoint at no cost, which would prevent traffic from being routed out through the NAT gateway. However, in this scenario the patches are downloaded from the internet.
        
        Answer D is correct and recommends to delete the existing NAT gateways. Deploy a NAT gateway in a separate egress VPC. Modify the transit gateway route tables to direct internet traffic to the egress VPC. It can become cost prohibitive to deploy a NAT gateway in every VPC because you pay an hourly charge for every NAT gateway you deploy. To centralize, you create a separate egress VPC and route all egress traﬃc from the VPCs through a NAT gateway that is in this VPC by using a transit gateway.
        
        How did you answer this question? Did you get it right the first time. Does the correct answer make more sense after we dove into each answer? Did you identify areas that you need more depth?
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        Great job!
        
- **Module 4: Network Security, Compliance and Governance**
    - Domain 4 Introduction
        
        Hi, and welcome back. Let's dive into Domain 4, where we will cover designing and implementation for security, compliance and governance. Domain 4 will cover 24% of the exam, so you can expect about 16 questions related to network security, compliance and governance.
        
        Domain 4 is broken into three task statements. The first task statement is: implement and maintain network features to meet security and compliance needs and requirements. The second task statement is: validate and audit security by using network monitoring and logging services. The third task statement is: implement and maintain confidentiality of data and communication of the network.
        
        To follow along or dive deeper, scan the QR code for a link to the Exam Guide.
        
        In this module, you will apply your knowledge to secure inbound, outbound and inter-VPC traffic; leveraging services such as Amazon Application Firewall, AWS Shield, network ACLs, and Gateway Load Balancer.
        
        We will also examine the security of the environment through monitoring and logging services, including but not limited to CloudWatch, VPC Flow Logs, Cloud Trail, and Route 53. And lastly, we will establish encryption solutions to secure confidentiality of network data and communication, such as using TLS, VPN over Direct Connect, and Application and Network Load Balancers.
        
        You may notice that we have discussed some of these services and topics in previous domains. However, in this module, we will be specifically targeting security and compliance in relation to your network; whereas the other modules discuss security services and features in relation to design, implementation, and management.
        
        Now that we have a clear understanding of what this module will present, let's get started with our first task statement. I'll see you in the next video!
        
    - Security and compliance requirements
        
        Welcome back! Let's dive into our first task statement for Domain 4: Security and compliance requirements. Throughout this course, we have discussed everything from network design, to implementation, to management and operations. But, what about ensuring your network is secure and meeting compliance requirements? This task statement focuses on implementing and maintaining network features to meet security and compliance requirements. Throughout this lesson we will be focusing on two topics related to the task statement.
        
        In our first topic, we will discuss AWS network architecture that meets security requirements. In our second topic, we will review threat modeling based on application architecture. With a focus on threat modeling, we can be fully prepared to meet compliance requirements.
        
        Let's begin by taking a deep dive into AWS services as it relates to networking security and compliance pertaining to threat modeling, security features, mechanisms, and automation. It's important to know the services, and then understand their functions and integrations. Ultimately, threat modeling requires thought, brainstorming, collaboration, and communication. AWS addresses its threat model in three different ways; separation of duty, least privilege, and need to know.
        
        After you have determined that your workload is suitable for deployment on AWS, the next step is to determine which services may be used and how they may be used in order to meet legal or regulatory framework requirements. For the exam, it will be significant to understand the importance of route tables, subnets, AWS Web Application Firewall, AWS Shield, security groups and network ACLs which play in the security of your environment.
        
        From a network security perspective, you should understand how the allocation of subnets and route tables enables you to construct architectures that promote secure operation. Not only will you need to identify these services, you will also need to know how they integrate with one another. For example, it is common for customers to place internet-facing load balancers into dedicated public subnets.
        
        This approach allows you to apply fine-grained controls on the routing within the subnet, implement network ACLs at the subnet boundary, configure security group rules on the load balancer's elastic network interfaces, and limit resources access in the subnet with an IAM policy. With these four levers, you have precise control over the flow of traffic into and out of your infrastructure.
        
        As discussed in previous modules, automation plays a key role in network security. In terms of network security, automation reduces the risk of human error. Tools like AWS Organizations, CloudFormation, and AWS Service Catalog allow you to control change within your environment, enforce standards, and implement guard rails. Automation can dramatically improve your overall security posture.
        
        Let's take a look at our first topic, AWS network architecture that meets security requirements. Defense in depth serves as a guiding principle in securing your environment. It is also important to keep in mind that network security is a shared responsibility between AWS and the customer. The customer controls what security to choose to implement and protect your content, platform, applications, system and network. AWS protects the security of the cloud.
        
        The question we should ask ourselves is, "How can we run our application in a secure environment?" It is important to have multiple mechanisms to secure your application to ensure it meets the highest security and compliance requirements. There isn't just one service that can meet all these needs. Rather, we want to ensure we have layers of access control, where we add security tools in front of one another to create the most secure and compliant application.
        
        One method for detecting network anomalies in your environment is to understand traffic flow patterns. For this exam, you should know how to secure inbound and outbound traffic flows from AWS. Security groups and Network ACLs are first used within your VPC to control traffic flows. They are the most basic services.
        
        For your exam, you will need to understand how services like Elastic Load Balancing protects your VPC resources. With Elastic Load Balancing, you define the ports and protocols it will accept, in turn minimizing the attack surface. Elastic Load Balancing proxies' connections to your VPC resources to avoid common attacks like SYN floods, which manipulates the TCP handshake, are not seen because only-well-formed TCP connections result in data flow to your resource.
        
        If you migrate a legacy application behind a load balancer that uses TCP, what type of load balancer do you configure for the new infrastructure to ensure the IP address for all incoming requests are recorded? You also need to understand how to protect traffic using route tables and subnets. You can use VPC endpoints and VPC peering to keep traffic within the AWS infrastructure without attaching an Internet gateway or Virtual gateway to your VPC. Dive deeper into IAM policies, including resource policies, and how to secure service endpoints.
        
        If your organization runs an application on instances in a public and private subnet and stores sensitive information in an S3 bucket that has an attached S3 endpoint, what would you do to secure the S3 bucket that holds sensitive information to ensure only instances from the private subnet can access the S3 bucket using the endpoint? You can modify the bucket policy to include the VPC Endpoint Identifier to ensure only traffic from the VPC endpoint can access the S3 bucket. VPC endpoints add the private connection to your resources without needing an internet gateway or NAT gateway.
        
        An overall governance approach is essential to a holistic security approach in the cloud. It is important to remember that when VPCs, IAM principles, or sensitive datasets are created ad hoc, without oversight or process, your workloads are exposed to significant risks.
        
        This task statement for Topic 2 touches on threat modeling and compliance. Threat modeling is fundamental to the understanding of risk. AWS has its own threat model for the environment on the AWS side of the shared responsibility model, which drives many design decisions for the underlying AWS environment.
        
        Through implementing mitigation strategy best practices for each part of the network flow between users and your environment, you can ensure you have resilience against different threat models. In AWS Regions, DDoS attacks are detected by AWS Shield which automatically baselines traffic, identifies anomalies, and, as necessary, creates mitigations.
        
        You can use AWS Shield as part of your DDoS-resilient architecture to protect both web and non-web applications. You can also utilize AWS services that operate from edge locations, such as CloudFront, Global Accelerator, and Route 53 to build comprehensive availability protection against all known infrastructure layer attacks; such as UDP reflection in Layer 3 or SYN flood in Layer 4. Many of the techniques discussed so far are effective at mitigating the impact that infrastructure layer DDoS attacks have on your application's availability.
        
        To defend against application layer attacks, you need to implement an architecture that allows you to specifically detect, scale to absorb, and block malicious requests. AWS web application firewall lets you monitor the HTTP and HTTPS requests that are forwarded to CloudFront, and lets you control access to your content. This task statement discussed security and compliance in depth.
        
        Let's go check out the second task statement from Domain 4: Networking Security, Compliance and Governance.
        
        Scan the QR code for a link to the Exam Guide to follow along, and I'll see you in the next video!
        
    - Security monitoring
        
        Welcome back! Let's dive into our second lesson in Domain 4: Security monitoring. In our first lesson, we detailed security and compliance requirements.
        
        Now, it's time to shift our focus to monitoring for your network environment. We will focus on task statement 4.2: Validate and audit security by using network monitoring and logging services. We will be breaking up our task statement into two topics: monitoring and logging.
        
        It is important to understand that monitoring helps you manage application performance, while logging is all about feeding the data for monitoring. Let's dive into our first topic for this task statement and look at network monitoring services that are available in AWS. AWS offers managed security services to assist in monitoring your network environment.
        
        For example, when you are rationalizing the layers of security around applications running on your Amazon EC2 instances, are you prepared to detect active threats? Both Amazon GuardDuty and Amazon Inspector can support these actions. AWS also offers Amazon Macie which identifies threats with respect to data in Amazon S3.
        
        For the exam, you should understand the capabilities of each of these managed AWS security services. It is also important to understand how CloudWatch can be used to centralize network operations. Consider the scenario where you want to monitor inbound TCP traffic to your VPC and that flow log data is stored in CloudWatch. You can create a CloudWatch alert that can be triggered by certain events defined and configured by the user. We will discuss alerting more in depth in the next topic.
        
        We discussed the importance of automation in network security in our last lesson, and it still remains true in terms of monitoring. It is always recommended that you automate monitoring tasks as much as possible. Why is that?
        
        Well, automation allows for faster analysis and should a host on your network be compromised, faster detection and intervention to ensure you maintain reliability, operational excellence, and performance efficiency for your network. It is important to understand that once failures, intrusions, attacks and other security threats are detected, action can be taken to block the source of the attack.
        
        Route 53 can perform health checking and you can receive notifications when a resource becomes unavailable and choose to route internet traffic away from unhealthy resources. When studying for the exam, it's important to know all of the monitoring options available within your AWS environment. While CloudWatch is the most widely used service, be sure to research what other options are available for monitoring the network infrastructure and application.
        
        Now that we understand the expectations related to network monitoring, let's move on to our second topic; network logging and alerting services that are available in AWS. It is important to understand that one of the unique strengths of a cloud environment is the fact that all asset creation and modification operations can be performed via an API. We talked about this earlier in this course. APIs are a single point of control, visibility, and audit. AWS provides a number of logging capabilities for the APIs themselves.
        
        For the exam, it is important for you to understand what logs can be generated by which AWS services, and where those logs are recorded. What AWS logging services aggregate those logs, what tools exist to analyze them and alert you. And lastly, know how to act on events of interest. AWS provides a number of logging capabilities for the APIs themselves through leveraging CloudTrail. However, not every service will store its logs to CloudTrail or CloudWatch, by default.
        
        It is important to understand the boundary of the AWS logging services and the type of information that is being collected. For example, VPC Traffic Mirroring is configured by the AWS API. Once configured, CloudWatch can be used to gather metrics on the state of VPC Traffic Mirroring, such as, whether the mirroring is active, or the number of mirrored packets successfully captured or dropped. However, the information within the packet is not logged within CloudWatch. Rather, that information is stored in the S3 bucket or an appliance you designate.
        
        For the exam, it is important to know how to graph metrics using CloudWatch. For example, graphing can be used to identify degrading performance or spikes in utilization. You should know how to use CloudWatch metrics to visualize the health and performance of your network infrastructure. You should also understand how to store and get basic metrics from text logs using CloudWatch logs. Log groups can have metric filters attached to them that allow metrics to be extracted and graphed using CloudWatch.
        
        These tools and features give you the visibility you need to spot issues before they impact the business and allow you to improve security posture and reduce the risk profile, of your environment. Each of the services listed play an important role in security monitoring. But also know how to integrate the services with one another to provide a comprehensive and seamless approach to security monitoring.
        
        It is important to discern the differences between logging, monitoring, and alerting to best understand practical ways of implementing them to create a secure network environment. Logging should be used to record data that is captured. With monitoring, you are observing specific data points. And alerting should be used to set up an automation that sends an alert when the threshold in data is exceeded. A series of failed log in attempts could indicate an active intrusion threat.
        
        Have you considered how you would protect against unauthorized SSL Attempts? How would monitoring, logging and alerting aid in identifying someone attempting to log into your server to compromise your network? You should also be considering a method for detecting network anomalies in your environment to understand traffic flow patterns.
        
        For example, let's say your server sends 1 gigabyte of data per day, and suddenly, it's sending 10 gigabytes per day. This could indicate an active data exfiltration.
        
        Think about how you can gain visibility and analyze your flow data from your VPC. What about considering how you would automate third-party detection data in your own response actions? These services can work together to provide you the solutions you are looking for.
        
        For the exam, you should understand the integration points that are available in AWS services for detection and response. In relation to this task statement, we dove into logging, monitoring and alerting for network security. We discussed different scenarios and requirements.
        
        Scan the QR code for a link to the Exam Guide to follow along.
        
        Let's get started with our last task statement from Domain 4: Security with encryption and I'll see you in the next video.
        
    - Security encryption
        
        Welcome back to our third and final lesson in Domain 4, security encryption. This task statement focuses on implementing and maintaining confidentiality of data and communications of the network. AWS helps to add a layer of security to your data in transit and at rest in the cloud providing scalable and efficient encryption features.
        
        If you remember in the first lesson of this module, we discussed the importance of defense in-depth. Encryption is a critical component of a defense in-depth strategy because it can mitigate weaknesses in your primary access control mechanism and transmission protocols.
        
        For your exam, you will need to understand both encryption services and encryption protocols to meet application compliance requirements. Our first topic will take a deep dive into the encryption solutions, then our second topic will discuss encryption methods. To get the most from an encryption solution, there will be many variables to be aware of for encryption of data in transit and data at rest.
        
        A few questions you should be asking yourself are do you have the proper access controls in place on your systems to prevent unauthorized individuals from compromising your keys? Are you using the appropriate algorithm for the portion of your network you're trying to secure? Are you aware of when to leverage 256 versus 128-bit encryption keys? And lastly, are you aware of the integrity of your algorithm to ensure compliancy? It is important to understand when an encryption solution is necessary and which protocols is appropriate to comply with your company policies or government industry regulations.
        
        If you were tasked with a new requirement to ensure that all data is encrypted before it is persisted to storage for an application running on Amazon RDS using a Microsoft SQL engine, how would you configure that SQL database to ensure all personally identifiable information is encrypted before storage and automatically decrypted when retrieved. For this exam, you have to understand AWS-managed services such as RDS and what protocols can be used. RDS supports transparent data encryption to encrypt stored data on your database instances running Microsoft SQL Server.
        
        Once you have made those determinations, think about best practices as it relates to managing your encryption keys. The best practice to maximize key security is using a hardware security module or HSM. AWS offers two services using HSMs with tamper response to protect customer's keys. AWS key management service, which manages a fleet of HSMs on the customer's behalf and AWS Cloud HSM, which gives customers the ability to manage their own HSMs. For example, each service can create keys on your behalf or you can import keys from your on-premises system to be used by each service. For the exam, it will be important to understand Cloud HSM and AWS KMS. It's essential to have a clear understanding of the AWS shared responsibility model as it relates to encryption. How can you ensure there is an end-to-end data protection? There are many versatility to avoid cryptographic pitfalls.
        
        Let's take a look at our second topic and dive into encryption methods. By default, AWS recommends that customers encrypt data at rest where supported. It is also important to have a clear understanding of the different protocols involved with encryption in transit as it is a more flexible approach. As you prepare for the exam, think about encryption at each layer and encryption in a variety of environments.
        
        For example, MACsec, IPsec, TLS, or HTTPS. Are you looking to secure a connection between an IP phone in a user's office to the corporate phone server on site or what about an encryption solution to connect a remote office to a common company internet? Think about using a web browser to connect to a secure website through HTTPS from the public network. As you set up security and encryption in your environment, there will be a few identifiers that need to be determined. For example, first, you will need to identify how your application is physically connecting to AWS. Second, do you want all of your traffic encrypted or do you only want a subset of traffic encrypted? There may be multiple channels of data communication between end users and the system deployed on AWS.
        
        For example, let's say you create a site-to-site VPN that would cross the internet. You could create a secure tunnel from your on-premises environment to AWS using IPsec. Another example may be to look at leveraging AWS Direct Connect with a dedicated circuit to isolate your company's traffic between your on-premises location and AWS from the internet. With this approach, you will be creating a private path for your network traffic, but it is not encrypted. Let's say your company does not require the entire circuit to be encrypted. Only certain administrative traffic needs that level of security. In that case, you may require that all AWS API command traffic use TLS encryption to ensure that sensitive credentials are not accidentally leaked. Essentially, we would be creating a site-to-site VPN connection on a direct connect connection.
        
        For your exam, understanding how to prevent DNS spoofing is important. We've discussed DNS architectures in module two, lesson four, but how can we protect DNS? If you were tasked to protect your organization's publicly accessible portal to secure sensitive financial information, what would you configure in Route 53 to protect interception of DNS queries? We've mentioned this many times, but by configuring DNS set in Route 53, you can create protection against man in the middle attacks. The various encryption protocols mentioned coupled with the encryption algorithms will assist in keeping your data safe in a number of different situations. It is essential to remain vigilant in relation to security protocols.
        
        That wraps up Domain 4, but always remember, AWS offers you the ability to add a layer of security to your data by providing scalable and efficient encryption features. For the exam, it will be essential to establish encryption solutions and methods to secure confidentiality of network data and communication.
        
        Scan the QR code for a link to the exam guide to review or dive deeper as part of your own exam readiness.
        
        Up next, you can engage in our last walk through question for Domain 4. I'll see you in the next video.
        
    - Walkthrough Question 7
        
        Hi and welcome back, let's dive into another walk through question.
        
        Let’s dive into our final question.
        
        A company is deploying a new web application to an Amazon EC2 Auto Scaling group that is behind an Application Load Balancer (ALB). The web application will serve a global audience and must have the highest level of performance possible. The company is implementing a compliance program that will require the application to support end-to-end encryption of specific sensitive data in transit. The company wants to use a private domain with corresponding TLS certificates from a public certificate authority (CA) for encryption.
        
        Which solution will meet these requirements?
        
        So for this question, what key words and phrases can you identify? How about global audience, highest level of performance, end-to-end encryption, and private domain, TLS certificates, and public certificate authority (CA). The question is asking which solution meets the requirements for end-to-end encryption for their sensitive data.
        
        So now let's look at the answers:
        
        A is to Create a certificate with AWS Certificate Manager (ACM). Deploy the certificate to an ALB HTTPS listener. Retrieve the root key from ACM to encrypt the traffic between the ALB and the EC2 instances. Register the ALB as the origin to a new Amazon CloudFront distribution.
        
        B is to Create a certificate with AWS Certificate Manager (ACM). Deploy the certificate to a new Amazon CloudFront distribution. Configure field level encryption by specifying fields in POST requests that need to be encrypted. Set the ALB as the origin for the CloudFront distribution..
        
        C is to Purchase a certificate from a public certificate authority (CA) and download the root encryption key. Deploy the certificate to a root key on the EC2 instances and configure HTTPS. Create a new Amazon CloudFront distribution. Register the ALB as the origin of the CloudFront distribution..
        
        D is to Purchase a certificate from a public certificate authority (CA) and download the root encryption key. Deploy the certificate to a root key on the EC2 instances and configure HTTPS. Deploy the certificate to an ALB HTTPS listener. Register the ALB as the origin to a new Amazon CloudFront distribution.
        
        Let’s dive deeper into each answer and see why the best choice answer is the best choice.
        
        So answer A is incorrect and recommends to let ACM handles the creation, storage, and renewal of public and private SSL/TLS certificates. You can apply an ACM certificate to an ALB HTTPS listener. This process checks for connection requests on the HTTPS port. However, you cannot retrieve private or root certificate keys from ACM for deployment to EC2 instances.
        
        Answer B is correct and recommends to let ACM handles the creation, storage, and renewal of public and private SSL/TLS certificates. CloudFront is a web service that speeds up distribution of your static and dynamic web content. You can apply an ACM certificate to a CloudFront distribution. The CloudFront distribution can offload the work of the TLS decryption and then re-encrypt sensitive data with field-level encryption. This configuration encrypts the sensitive content while the traffic passes through the ALB HTTP listener. The sensitive content is decrypted only when the content reaches the EC2 instance. This solution would provide end-to-end encryption for the sensitive data in this application.
        
        Answer C is incorrect and recommends to use CloudFront which is a web service that speeds up distribution of your static and dynamic web content. An ALB can automatically distribute incoming traffic across multiple EC2 instances. To allow the clients to establish an end-to-end encrypted connection, you would need to deploy TLS certificates to CloudFront as well as to the ALB. The services in this scenario are incorrectly configured.
        
        Answer D is incorrect and recommends to use CloudFront which is a web service that speeds up distribution of your static and dynamic web content. An ALB can automatically distribute incoming traffic across multiple EC2 instances. To allow the clients to establish an end-to-end encrypted connection, you would need to deploy TLS certificates to CloudFront as well as to the ALB and the EC2 instances. The services in this scenario are incorrectly configured.
        
        How did you answer this question? Did you get it right the first time. Does the correct answer make more sense after we dove into each answer? Did you identify areas that you need more depth?
        
        Now I always recommend you go back to your two answers that are possibly correct and re-read each and choose your best choice answer.
        
        Great job!

