# VPC



![](../../../.gitbook/assets/image%20%281%29.png)

## VPC \(Virtual Private Cloud\)

When we create am AWS account, a default VPC is created for us.

## AWS Global Infrastructures

Region, Availability Zone \(AZ\), Data Center 

## How data travels through AWS architecture

IGW - Route Table - NACL - VPC - Subnet

## Internet Gateways

Analogy : Modem

* A VPC can only have one IGW

## Route Tables

Analogy: Router

{% embed url="https://linuxacademy.com/cp/courses/lesson/course/2746/lesson/3/module/241" caption="starts from 1:09" %}

#### Default route Table for a default VPC has two routes

<table>
  <thead>
    <tr>
      <th style="text-align:left">Destination</th>
      <th style="text-align:left">Target</th>
      <th style="text-align:left">Status</th>
      <th style="text-align:left">Explanation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">172.31.0.0/16</td>
      <td style="text-align:left">local</td>
      <td style="text-align:left">Active</td>
      <td style="text-align:left">
        <p>This is the IP range assigned for VPC when it is created.</p>
        <p></p>
        <p>This indicates that the IP address destined to 172.31.0.0/16 ip range
          (or, the local subnet) should only directed to this VPC.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">0.0.0.0/0</td>
      <td style="text-align:left">lgw-12dcwe6s</td>
      <td style="text-align:left">Active</td>
      <td style="text-align:left">
        <p>0.0.0.0/0 indicates any ip address range that is outside of previously
          mentioned. So, Any ip address that is not destined to 172.31.0.0/16 range
          should be directed to the internet gateway, which means to go outside the
          gateway and ultimately to the internet.</p>
        <p></p>
        <p>If for any reason, IGW is detached from the gateway, Status columns becomes
          from &quot;Active&quot; to &quot;Blackhole&quot;, and the communication
          is lost.</p>
      </td>
    </tr>
  </tbody>
</table>## Network Access Control List

Analogy: Firewall, poking holes

Network ACLs are stateless. What that means is you must have rules to allow traffics to flow. \(like poking holes to the wall\)

* Inbound rules - controls rules for traffics going into the subnet
* Outbound rules - controls rules for traffics going out of the subnet

#### default Inbound rules for VPC 

| Rule \# | Type | Protocol | Port Range | Source | Allow / Deny |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 100 | ALL Traffic | ALL | ALL | 0.0.0.0/0 | ALLOW |
| \*  | ALL Traffic | ALL | ALL | 0.0.0.0/0 | DENY |



## Subnets



{% embed url="http://www.steves-internet-guide.com/subnetting-subnet-masks-explained/" %}



## Availability Zones \(VPC specific\)









