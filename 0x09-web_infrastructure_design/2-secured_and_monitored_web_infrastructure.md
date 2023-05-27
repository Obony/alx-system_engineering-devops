
## Secured and monitored web infrastructure description :dolphin:

The diagram shows an integrated infrastructure that faciliatates data monitoring and encryption for traffic along the network.
in the setup, the firewalls serve to protect the network from unauthorized users trying to access it and forms a barrier between the external network and VPN users. The setup is particurlarly efficient for prevention of intermediary or man-in-the-middle attacks

The `SSL certificates` are vital for data encryption for messages sent between clients across the network, thereby protecting sensitive information from being exposed.

The purpose of having performance monitoring tools is to gauge how well the network components such as servers are able to carry out their mandated tasks.

## Key issues with the infrastructure

It would include a lack of scalability as the network only uses one MySQL server thereby creating a single point of failure
