<h1>WEBSITE HOSTING USING VIRTUAL MACHINES AND APPLICATION GATEWAY</h1>


<h2>Project Overview</h2>
This project focuses on architecting and implementing a simple web site end to end through Azure services which enables users to access the site from all over the world and also includes geography specific contents.

<h2>Architecture Diagram</h2>
 

1. Four Virtual machines are being created. First two in US region and another two in India region. This is where apache will be installed and web page will be created which        denotes each server and region.
2. Application gateway is created and placed in front of the Virtual machines where it is used to balance the traffic across each VM's so that load is shared equally avoiding      slowness in displaying the webpage
3. Traffic manager is implemented where it is used to decide which kind of routing needs to be done. Since our application is hosted in 2 geographies. We will be opting for        geographic routing method. Also the application gateways will be linked with traffic manager to function as expected
4. The endpoint of the traffic manager is linked with the DNS zone where we also need to link our domainname (created using freenom website) to the DNS zone.
5. Finally the name servers created in the DNS zone must be copied and pasted in name servers of the domain name which will be present in the website where the domain name was      created.

<h2>Resources/Topics covered as part of this Lab</h2>

·	Resource Group

·	Virtual Machine

·	Security groups

·	Apache Web server

·	Power shell

·	Virtual network

·	subnets

·	OS disks

·	Network interface

·	Ports:http,ssh

·	Application gateway(load balancer)

·	Public ip addresses

·	Traffic manager 

·	DSN zone

·	Name servers

For detailed instructions on how to accomplish above steps kindly refer file End to end website hosting-Project 1.docx


