A mindmap I built to help people with Azure Networking



```mermaid
mindmap
  root(("Azure Networking"))
    VNet(("VNet (Virtual Network)"))
      Subnet
        ("Availability Zones")
        ("NSG (Network Security Group)")
        ("Route Table")
        ("Private IP Range")
      Peering(("Peering"))
        ("VNet Peering")
        ("Global VNet Peering")
      ("Service Endpoints")
      ("Private Endpoints")
    VM(("Virtual Machine"))
      NIC(("NIC (Network Interface Card)"))
        ("IP Configurations")
          IPv4
            ("Private IP")
            ("Public IP")
          IPv6
        ("NSG Association")
    LoadBalancing(("Load Balancing"))
      ("Azure Load Balancer (L4)")
      ("Application Gateway (L7)")
      ("Traffic Manager (DNS-based)")
    Traffic(("IP Traffic Types"))
      ("UDP (Broadcast, Stateless)")
      ("TCP (Connection-oriented)")
      ("ESP and AH (IPSec)")
      ("ICMP (Ping, Diagnostics)")
    Security(("Firewall and Security"))
      ("Azure Firewall")
      ("DDoS Protection")
      ("NSG (Network Security Groups)")
      ("ASG (Application Security Groups)")
```
