# Learning About Linux 

## How Internet Actually Works?
    The Internet works through a hierarchy of connectivity. At the core, data centers and backbone providers host and route vast amounts of data. Tier 1 companies (like AT&T, CenturyLink, NTT, etc.) maintain global Internet backbones and connect with each other without paying transit fees (this is called peering).
    Internet Service Providers (ISPs), such as Tier 2 and Tier 3 providers, purchase bandwidth or connectivity from these backbone providers or larger ISPs.Finally, end users (individuals or businesses) connect to the Internet through these local ISPs.

## What are servers? 
    A system which serves to the client. like 
    file server: To get some file   
    database server: To save some data 
    Application server: To run some application 
    web server: To show some static data 

## How a URL is accessed? 
    When some URL is hit by the user, ISPs provide access to the internet. 
    youtube.com --- Domain 
    On which server this application is running is application server --- this will have some IP Address 
    To link this IP address and domain we have DNS Server -- which is domain name server.

## Difference between application server and web server?
    Web server serves static data and application server serves dynamic in which some computations and calculations are done.
    Like Nginx is web server and some server on which nodejs application is running is application server.

## Types of applications:
    1- Standalone Application: No need of internet connectivity, like on airports we have some feedback getting applications, no need of any other server like file or email servers.
    2- Web applications: Needs Internet connectivity, database server and all other required third parties. Running group of applications.

## What is Linux?
    OS is program or software which helps different applications to run.
    Linux is open source OS. 

## Difference between Unix and Linux?
    Unix is paid, like Macintosh. Its not open source. 
    Open source and free version is Linux.

## Ways to use Linux:
    1- WSL: Windows OS also has linux we have to just enable it.
    2- Virtual Box
    3- AWS / Azure, GCP, Cloud Virtual Machine
    4- Vagrant 
    