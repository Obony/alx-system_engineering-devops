
## Description of the infrastructure :dolphin:

This structure shows how the site 'www.foobar.com' is hosted without any firewalls or SSL certificates needed to protect the servers within the network. in the simplistic structure, all network components are reliant on the same resources that include the CPU, RAM and SSD.

## Specifics About This Infrastructure
1. A server is a computer hardware or software that provides services to other computers, referred to as *clients*.

2.The role of the Domain Name Server is to provide an appropriate match for a website name to its IP address. The DNS server associates the name of the website with its IP address
3. `www.foobar.com` uses an **A record**. This can be checked by running `dig www.foobar.com`

4.The web server is a software/hardware that accepts requests via HTTP or secure HTTP (HTTPS) and responds with the content of the requested resource or an error messsage.

5.The role of the application server.<br/>To install, operate and host applications and associated services for end users, IT services and organizations and facilitates the hosting and delivery of high-end consumer or business applications

6.The role of the database.<br/>To maintain a collection of organized information that can easily be accessed, managed and updated

7. What the server uses to communicate with the client (computer of the user requesting the website).<br/>Communication between the client and the server occurs over the internet network through the TCP/IP protocol suite.

##The key issues With This Infrastructure

Due to the overreliance of a single resource center, there are mutiple Single Points of Failure(SPOF) that could cause significant downtime in case of a technical issue.other issues include limited scalability and inefficience in maintenance during downtime
