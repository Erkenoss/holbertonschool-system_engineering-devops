# Web Infrastructure README

This README provides an overview of key concepts related to web infrastructure and the flow of a web request.

## Server Location and Types

- A server is typically hosted in a data center.
- Servers can be physical (hardware) or virtual (software-based).
- Servers run an operating system (OS) that manages their resources.

## Role of Servers

- A web server's role is to serve static web pages, which include HTML, CSS, and other static assets.
- An application server's role is to compute and deliver dynamic content to users.

## Database and DNS

- A database's primary role is to store application data securely.
- DNS (Domain Name System) translates domain names into IP addresses, allowing users to reach websites using friendly names.

## DNS Records

- An A record in DNS maps a domain name to an IP address.
- So, for example, www.foobar.com, <www> wwill be change in IP adress by A record.

## Deployment, SPOF and Scalability

- A single server in an infrastructure can be a single point of failure (or SPOF) due to a lack of redundancy.
- When new code is deployed, the web server might need to be restarted, causing temporary downtime.
- An infrastructure with a single server is not scalable and cannot handle traffic that exceeds the server's capacity.

## Network Communication

- Servers communicate over a network using the TCP/IP protocol.

## TCP/IP protocol

- TCP/IP is a data link protocol used on the Internet to enable computers and other devices to send and receive data.
- The acronym TCP/IP stands for Transmission Control Protocol/Internet Protocol. It allows devices connected to the Internet to communicate with each other across networks.

## ADD ELEMENT

- I have add a new flowchart: This file 1-distributed_web_infrastructure
- I have add HAproxy, a new web server, a new appli server and this own codebase.
- The Haproxy is a load-balancer. He is use for keep an eye on the trafic network and dispatch the different users between the different web server.
- The other web and appli server work as a pair, same for codebase. If we have one momre web server, we need a new appli server by convinience and for keep the trafic under control.

 ## NEW FEATURE

- 
