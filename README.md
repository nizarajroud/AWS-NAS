An analytics company uses Amazon QuickSight (Enterprise Edition) to easily create and publish interactive BI dashboards that can be accessed from any device. For a specific requirement, the company needs to create a private connection from Amazon QuickSight to an Amazon RDS DB instance that's in a private subnet to fetch data for analysis.

Which of the following represents an optimal solution for configuring a private connection between QuickSight and Amazon RDS DB instance?



Explication générale
Correct option:

Create a new private subnet in the same VPC as the Amazon RDS DB instance. Create a new security group with necessary inbound rules for QuickSight in the same VPC. Sign in to QuickSight as a QuickSight admin and create a new QuickSight VPC connection. Create a new dataset from the RDS DB instance

Amazon QuickSight Enterprise edition is fully integrated with the Amazon VPC service. A VPC based on this service closely resembles a traditional network that you operate in your own data center. It enables you to secure and isolate traffic between resources. You define and control the network elements to suit your requirements, while still getting the benefit of cloud networking and the scalable infrastructure of AWS.

By creating a VPC connection in QuickSight, you're adding an elastic network interface in your VPC. This network interface allows QuickSight to exchange network traffic with a network instance within your VPC. You can provide all of the standard security controls for this network traffic, as you do with other traffic in your VPC. Route tables, network access control lists (ACLs), subnets, and security groups settings all apply to network traffic to and from QuickSight in the same way that they apply to traffic between other instances in your VPC.

When you register a VPC connection with QuickSight, you can securely connect to data that's available only in your VPC, for example: 1. Data you can reach by IP address 2. Data that isn't available on the public internet 3. Private databases 4. On-premises data

This works if you set up connectivity between the VPC and your on-premises network. For example, you might set up connectivity with AWS Direct Connect, a virtual private network (VPN), or a proxy.

After you connect to the data, you can use it to create data analyses and publish secure data dashboards.

Incorrect options:

Amazon QuickSight Enterprise edition is fully integrated with the Amazon VPC service. Create an ENI in QuickSight that points to the VPC that hosts the RDS DB instance. However, the subnet has to be a private subnet and not a public subnet - When you create a VPC connection in QuickSight, an elastic network interface is added in your VPC. ENI is present on the VPC side and not on the QuickSight side of the connection.

Create a new private subnet in the same VPC as the Amazon RDS DB instance. Create a new network Access Control List (ACL) with necessary inbound rules for QuickSight in the same VPC. Connect from QuckSight using VPC connector - By creating a VPC connection in QuickSight, you're adding an elastic network interface in your VPC. You define a Security Group and not an NACL for an ENI.

Create a Private Virtual Interface between VPC that hosts Amazon RDS DB instance and QuickSight. Use this connection to privately access necessary data from RDS DB - A private virtual interface is used to access an Amazon VPC using private IP addresses. This interface is used by the AWS Direct Connect connection. This option has been added as a distractor.




The networking team at a global company has set up separate VPCs for applications managed by the Finance, Marketing, Audit and HR departments. You need to set up AWS Direct Connect to enable data flow from the on-premises data center to each of these VPCs. The company has monitoring software running in the Audit department's VPC that needs to collect metrics from the instances in all the other VPCs.

Due to budget constraints, the data transfer charges should be kept to a minimum. Which of the following solutions would you recommend for the given requirement?

Create four private VIFs, that is, one VIF each from the on-premises data center to each of the VPCs. Route traffic between VPCs using the Direct Connect link



Explication générale
Correct option:

Create four private VIFs, that is, one VIF each from the on-premises data center to each of the VPCs. Enable VPC peering between all VPCs

A Virtual Interface (VIF) is necessary to access AWS services, and can be either public, private or transit, like so:

Private virtual interface: A private virtual interface should be used to access an Amazon VPC using private IP addresses.

Public virtual interface: A public virtual interface can access all AWS public services using public IP addresses. A public virtual interface enables access to public services, such as Amazon S3.

Transit virtual interface: A transit virtual interface should be used to access one or more Amazon VPC Transit Gateways associated with Direct Connect gateways. You can use transit virtual interfaces with 1/2/5/10 Gbps AWS Direct Connect connections.

Direct Connect gateways only support routing traffic from Direct Connect VIFs to VGW (associated with VPC). VPC to VPC communication or VIF to VIF communication is not possible via Direct Connect gateways. Therefore, to send traffic between two VPCs, you must configure a VPC peering connection.

 

The given use case requires data flow from the on-premises data center to each of the VPCs, so you must create one VIF each from the on-premises data center to each of the VPCs. If you are using VPC peering, on-premises connectivity (VPN and/or Direct Connect) must be made to each VPC. Resources in a VPC cannot reach on-premises using the hybrid connectivity of peered VPCs.


Incorrect options:

Create four private VIFs, that is, one VIF each from the on-premises data center to each of the VPCs. Route traffic between VPCs using the Direct Connect link - As mentioned in the explanation above, you cannot route traffic between VPCs using a Direct Connect link. So this option is incorrect.

Create a private VIF to the Audit department's VPC. Peer this VPC to all the other VPCs - Just a single VIF to the Audit department's VPC would not suffice the requirement of having data flow from the on-premises data center to each of the VPCs. Resources in a VPC cannot reach on-premises using the hybrid connectivity of peered VPCs.

Create a public VIF to the Audit department's VPC. Peer this VPC to all the other VPCs - This option has been added as a distractor. You can only create a transit virtual interface to connect to a transit gateway, a public virtual interface to connect to public resources (non-VPC services), or a private virtual interface to connect to a VPC. So you cannot create a public VIF to connect to a VPC.




Question 3

The networking team at a company wants to set up an AWS Site-to-Site VPN connection between its on-premises data center and the AWS Cloud. The VPN connection should use dynamic routing and the team wants to make sure that tunnel A is preferred over tunnel B when sending traffic from AWS to the on-premises network.

Which solution would you recommend for this requirement?



Explication générale
Correct option:

Configure the VPN connection in an Active/Active configuration and advertise a more specific prefix for tunnel A

You can enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN (Site-to-Site VPN) connection, and configuring routing to pass traffic through the connection. A VPN connection refers to the connection between your VPC and your own on-premises network. Site-to-Site VPN supports Internet Protocol security (IPsec) VPN connections.

The type of routing that you select can depend on the make and model of your customer gateway device. If your customer gateway device supports Border Gateway Protocol (BGP), specify dynamic routing when you configure your Site-to-Site VPN connection. If your customer gateway device does not support BGP, specify static routing. If you use a device that supports BGP advertising, you don't specify static routes to the Site-to-Site VPN connection because the device uses BGP to advertise its routes to the virtual private gateway. If you use a device that doesn't support BGP advertising, you must select static routing and enter the routes (IP prefixes) for your network that should be communicated to the virtual private gateway.

A Site-to-Site VPN connection offers two VPN tunnels between a virtual private gateway or a transit gateway on the AWS side, and a customer gateway (which represents a VPN device) on the remote (on-premises) side.

To address the given requirement, you need to set the customer gateway device to prefer one VPN tunnel over the other by leveraging the order of preference criteria:

Advertise a more specific prefix to the virtual private gateway or transit gateway on the tunnel (Tunnel A for the given use case) that the customer prefers to receive traffic from AWS.

For matching prefixes where each VPN connection uses BGP, the AS PATH is compared and the prefix with the shortest AS PATH is preferred.

When the AS PATHs are the same length, and the first AS in the AS_SEQUENCE is the same across multiple paths, multi-exit discriminators (MEDs) are compared. The path with the lowest MED value is preferred.



Incorrect options:

Configure the VPN connection in an Active/Passive configuration and advertise a more specific prefix for tunnel B

Configure the VPN connection in an Active/Active configuration and advertise a more specific prefix for tunnel B

For the given use case, you need to advertise a more specific prefix for tunnel A as that's the preferred tunnel. So both these options are incorrect.
Configure the VPN connection in an Active/Passive configuration and advertise a more specific prefix for tunnel A - If the AWS VPN connection (dynamic routing type) has an Active/Passive configuration (tunnel A is UP, but tunnel B is DOWN), traffic from AWS to the on-premises network traverses tunnel A because it's in the UP state. So using a more specific prefix for tunnel A is irrelevant.



Question 6

A Network Engineer is setting up DNS failover configuration for Route 53. The engineer needs to use multiple routing policies (such as latency-based and weighted) to configure a more complex DNS failover.

Which of the following are the key points to consider while configuring a failover configuration on Route 53? (Select two)

Explication générale
Correct options:

Records without a health check are always considered healthy. If no record is healthy, all records are deemed to be healthy - If a record in a group of records that have the same name and type doesn't have an associated health check, Route 53 always considers it healthy and always includes it among possible responses to a query.

If none of the records in a group of records are healthy, Route 53 needs to return something in response to DNS queries, but it has no basis for choosing one record over another. In this circumstance, Route 53 considers all the records in the group to be healthy and selects one based on the routing policy and on the values that you specify for each record.

If you're creating failover records in a private hosted zone, you must assign a public IP address to an instance in the VPC to check the health of an endpoint within a VPC by IP address

If you're creating failover records in a private hosted zone, note the following:

Route 53 health checkers are outside the VPC. To check the health of an endpoint within a VPC by IP address, you must assign a public IP address to an instance in the VPC.

You can create a CloudWatch metric, associate an alarm with the metric, and then create a health check that is based on the data stream for the alarm.

Incorrect options:

If you're routing traffic to any AWS resources that you can create alias records for, you need to create health checks for these resources too - If you're routing traffic to any AWS resources that you can create alias records for, don't create health checks for those resources. When you create the alias records, you set Evaluate Target Health to Yes instead.

More than half of the configured records with nonzero weights must be unhealthy before Route 53 starts to respond to DNS queries using records that have weights of zero - All the records with non-zero weights must be unhealthy before Route 53 starts to respond to DNS queries using records that have weights of zero.

When responding to queries, Route 53 includes only the healthy primary resources for active-active failover configuration - In active-active failover, all the records that have the same name, the same type, and the same routing policy are active unless Route 53 considers them unhealthy. Route 53 can respond to a DNS query using any healthy record.

In active-passive failover, when responding to queries, Route 53 includes only the healthy primary resources. If all the primary resources are unhealthy, Route 53 begins to include only the healthy secondary resources in response to DNS queries.

Question 9
A VPC is deployed with a 10.2.0.0/16 CIDR block. The networking team is reviewing DHCP options, and there is disagreement about the valid DNS addresses available for the VPC.

Which of the following addresses are valid IP addresses provided by Amazon for this scenario? (Select two)



Explication générale
Correct options:

10.2.0.2

169.254.169.253

Domain Name System (DNS) is a standard by which names used on the internet are resolved to their corresponding IP addresses. A DNS hostname is a name that uniquely and absolutely names a computer; it's composed of a hostname and a domain name. DNS servers resolve DNS hostnames to their corresponding IP addresses. Public IPv4 addresses enable communication over the internet, while private IPv4 addresses enable communication within the network of the instance (either EC2-Classic or a VPC).



To support DNS resolution, Amazon provides DNS server at the 169.254.169.253 IPv4 address or the reserved IP address at the base of the VPC IPv4 network range plus two. So for the given use case, 10.2.0.2 is also reserved by Amazon for DNS resolution.

The Dynamic Host Configuration Protocol (DHCP) provides a standard for passing configuration information to hosts on a TCP/IP network. The options field of a DHCP message contains configuration parameters, including the domain name, domain name server, and the netbios-node-type. By default, all instances in a nondefault VPC receive an unresolvable hostname that AWS assigns (for example, ip-10-0-0-202). You can assign your own domain name to your instances, and use up to four of your own DNS servers. To do that, you must create a custom set of DHCP options to use with the VPC.


Incorrect options:

10.0.0.2

10.1.0.2

169.254.169.254

These three options contradict the explanation provided above, so these options are incorrect.



Question 13
A company has decided to adopt IPv6 for its network. As an intermediary step in the path to fully adopting IPv6, the company is looking for dual-stack IPv4/IPv6 designs. To kickstart the change, the company has picked a straightforward hybrid network that consists of an on-premises connection to AWS over a Site-to-Site VPN connection via a Transit Gateway and an AWS Direct Connect connection between AWS and the on-premises data center.

As a Network Engineer, which of the following measures would you suggest to meet the given requirements? (Select three)

AWS Transit Gateway does not support IPv6 traffic. Hence, VPC peering should be considered for dual-stack traffic


Explication générale
Correct options:

For AWS Direct Connect connection, reuse your existing VIFs and enable them for dual-stack support

To use your Direct Connect connection for dual-stack traffic, you need to create one of the following virtual interfaces (VIFs): Private VIF, Public VIF, or Transit VIF, or reuse your existing VIFs and enable them for dual-stack support. The following considerations apply to dual-stack VIFs: 1. A virtual interface can support a BGP peering session for IPv4, IPv6, or both (dual-stack). 2. For the IPv6 stack, Amazon automatically assigns a /125 IPv6 CIDR for the BGP peering connection. 3. On Public VIFs, you must advertise to AWS /64 prefixes or larger.



For dual-stack connectivity on the Site-to-Site VPN connection via a Transit Gateway, you need to create two VPN connections, one for the IPv4 stack and one for the IPv6 stack

Your Site-to-Site VPN connection on a Transit Gateway can support either IPv4 traffic or IPv6 traffic inside the VPN tunnels. This means that for dual-stack connectivity, you need to create two VPN connections, one for the IPv4 stack and one for the IPv6 stack. For the Site-to-Site VPN connection, you intend to use for IPv4 routing, each tunnel will have a /30 IPv4 CIDR in the 169.254.0.0/16 range, while for the VPN connection intended for IPv6 routing, each VPN tunnel will have two CIDR blocks: one /30 IPv4 CIDR in the 169.254.0.0/16 range and one /126 IPv6 CIDR in the fd00::/8 range.


To configure an IPv6-enabled VPC attachment for the Transit Gateway, the VPC and the attachment subnets need to have associated IPv6 CIDRs. The remaining Transit Gateway configurations continue to have the same functionalities across both stacks

AWS Transit Gateway is a network transit hub that you can use to interconnect your VPCs and hybrid networks for both IPv4 and IPv6 stacks. All Transit Gateway concepts and constructs – attachments, peering connections, associations, propagations, and routing – continue to have the same functionalities across both stacks. Note that to configure an IPv6-enabled VPC attachment to the Transit Gateway, the VPC and attachment subnets need to have associated IPv6 CIDRs.


Incorrect options:

AWS Site-to-Site VPN connection on a Transit Gateway can support both IPv4 traffic and IPv6 traffic inside the VPN tunnels. Hence, no changes are required on this connection

To use Direct Connect connection for dual-stack traffic, you need to create separate virtual interfaces (VIFs- Private VIF or Public VIF or Transit VIF) for each stack

AWS Transit Gateway does not support IPv6 traffic. Hence, VPC peering should be considered for dual-stack traffic

These three options contradict the explanation provided above, so these options are incorrect.




Question 15

A retail company operates its IT infrastructure in a hybrid cloud configuration with the on-premises data center connected to the AWS Cloud via an AWS Site-to-Site VPN connection. The networking team has set up an AWS VPC with a CIDR range of 172.31.0.0/16 and the on-premises network has a CIDR range of 172.31.1.0/24. The VPC's route table also has a propagated route to a virtual private gateway with a destination of 172.31.1.0/24.

Which of the following represents a correct statement regarding the routing for traffic destined to the on-premises network?


Explication générale
Correct option:

The on-premises network would be unreachable as the local route would be preferred for all traffic destined for 172.31.1.0/24

You can enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN (Site-to-Site VPN) connection, and configuring routing to pass traffic through the connection. A Site-to-Site VPN connection offers two VPN tunnels between a virtual private gateway or a transit gateway on the AWS side, and a customer gateway (which represents a VPN device) on the remote (on-premises) side. When you create a Site-to-Site VPN connection, you must specify the type of routing that you plan to use (static or dynamic) and update the route table for your subnet.


If propagated routes from a Site-to-Site VPN connection or AWS Direct Connect connection overlap with the local route for your VPC, the local route is most preferred even if the propagated routes are more specific. For the given use case, the on-premises network would be unreachable as the local route would be preferred for all traffic destined for 172.31.1.0/24.


Incorrect options:

All traffic destined for 172.31.1.0/24 is routed via the virtual private gateway - This option is incorrect as the local route is most preferred even if the propagated routes are more specific since we have an overlap.

All traffic destined for 172.31.1.0/24 is routed via the internet gateway

All traffic destined for 172.31.1.0/24 is routed via the virtual private gateway or the internet gateway

These two options have been added as distractors since the use case does not mention having an internet gateway attached to the given VPC.


