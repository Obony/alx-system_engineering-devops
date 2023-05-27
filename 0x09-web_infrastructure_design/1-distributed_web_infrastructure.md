
## Distributed web infrastructure description :dolphin:

This web infrastructure shown in the diagram is an upgrade on the simple LAMP infrastructure as it enhances the efficiency of network by distributing load to a replica server with a load balancer which acts as intermediary between the client and the web servers.

The load balancer utilizes the Round Robing algorithm which relies on turns to assign requests, distributing them efficiently and balancing them accordingly in the setup one servers acts as the master which can perform read/write requests while slave server can only process read requests.

##Key issues with the infrastructure
Just as is the case with the simple LAMP infrastructure, the setup has mutiple Single Points of Failure(SPOF). for example any downtime in the master server could result in the incapability of clients being able t write data to a database
