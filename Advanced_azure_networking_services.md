## Azure Networking Services

#### 1. Azure Application Gateway & WAF

Routes HTTP/HTTPS traffic to web applications. Provides application-level traffic routing and security.
- Features:
  - Load balancing
  - SSL/TLS termination
  - Web Application Firewall (WAF)

<img src="https://learn.microsoft.com/en-us/azure/application-gateway/media/how-application-gateway-works/how-application-gateway-works.png" alt="Azure Application Gateway" width="700">


#### 2. Azure Load Balancer

Distributes network traffic across virtual machines at Layer 4 (TCP/UDP).
- Features:
  - Traffic distribution
  - Integration with Availability Sets
  - Inbound and outbound traffic balancing

#### 3. Azure DNS

Hosts DNS domains and translates domain names into IP addresses.
- Features:
  - Domain hosting and name resolution
  - Integration with Azure services
  - Globally distributed DNS infrastructure

#### 4. Azure Firewall

Managed, stateful network security service that filters and controls network traffic.
- Features:
  - Stateful traffic filtering
  - Application FQDN filtering
  - Threat intelligence-based filtering

#### 5. Virtual Network (VNet) Peering

Connects two Azure Virtual Networks privately using Azure's backbone network.
- Features:
  - Global VNet Peering across regions
  - Direct communication between peered VNets
  - Non-transitive connectivity by default

#### 6. VNet Gateway

Connects Azure Virtual Networks to other networks through VPN or ExpressRoute.
- Features:
  - Site-to-Site VPN
  - Point-to-Site VPN
  - ExpressRoute connectivity

#### 7. VPN Gateway

Provides encrypted VPN connectivity between Azure and on-premises or remote networks.
- Features:
  - IPsec/IKE VPN protocols
  - High availability configurations
  - BGP support for dynamic routing
