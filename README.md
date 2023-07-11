# Network-Design-for-Small-Medium-Business-(SME)
Network Design for Small and Medium-Sized Enterprises (SMEs)

This network architecture concept is intended to meet the needs of a Small-Medium Enterprise (SME) with three major departments: engineering, sales, and management. The network infrastructure should be able to meet the company's present demands while also enabling future growth and modifications.

The Engineering department has 260 staff PCs as well as 40 production servers. The servers are distributed in groups of five, for a total of eight groups. Each group employs two servers for hot-swap load balancing, with the remaining three servers dedicated to service delivery. Load balancing is accomplished via redundant load balancers, which ensures resiliency. The customer load is spread uniformly throughout the production servers, and the load balancers are in hot-standby mode.

The Sales department includes a variety of users, including four technical writers, four customer service representatives, two office-based salespeople, and roughly 20 salespeople who regularly travel. These different requirements should be considered in the network architecture for sales. Four computers are dedicated to writing, four to customer service, and thirty to visiting salesmen. For remote access, a VPN server is also required, with a similar service production unit (SPU) setup as in the Engineering department. VPN traffic is moderate, with a limit of 30 clients per hour, with active sessions generating up to 10Mbps of data.

The Management department is made up of a small group of five people that require dedicated PCs. This comprises the CEO, Technical Lead (TL), Sales Lead (SL), Economic Officer, and others.

Furthermore, shared resources such as 10 printers and 2 file servers for sales and management should be incorporated into the network design.

To meet these criteria, the proposed network architecture incorporates a mix of layer 2 and layer 3 devices to provide for effective communication and connectivity across departments and sub-departments. To guarantee suitable segmentation, subnets will be constructed for each sub-department inside the departments.

This complete network design seeks to build a scalable and robust infrastructure capable of meeting the present demands of the SME as well as future growth and modifications. The network architecture facilitates efficient operations and encourages cooperation within the organisation by taking into account the specific requirements of each department.
