# Apache-Load-Balancer

This repository is to demonstrate an example of horizontal scaling, with Apache as a load balancer. 

### Vertical vs. Horizontal Scaling 

If you have a website or application serving users in 2021 and beyond, your chances of going viral online or having great targeted marketing are pretty good, and you (yes, you!) could be minutes from serving on average 1000 to 1 million users to your website or application.

When you have just one Web server and the load increases, of course you want to serve more and more customers. So what you can do is add more CPU and RAM or completely replace the server with a more powerful one - this is called “vertical scaling”. This approach has limitations - at some point you reach the maximum capacity of CPU and RAM that can be installed into your server.

Another approach used to cater for increased traffic is “horizontal scaling” - distributing load across multiple Web servers. This approach is much more common and can be applied almost seamlessly and almost infinitely (you can imagine how many server Google has to serve billions of search requests).

Horizontal scaling allows to adapt to current load by adding (scale out) or removing (scale in) Web servers. Adjustment of number of servers can be done manually or automatically (for example, based on some monitored metrics like CPU and Memory load).

The capability of a system to be able to handle a growing load by adding resources is called "Scalability"

In the [Devops-Tooling-Web-Solution](https://github.com/chauntelkellar/Devops-Tooling-Web-Solution) there were 3 web servers and each of them had its own public IP address and public DNS name and a client had to access them by using different URLs.  In this repository, we will hide this complexity and have a single point of access with a single public IP address/name by utilizing a Load balancer. A Load Balancer (LB) distributes clients’ requests among underlying Web Servers and makes sure that the load is distributed in an optimal way.


Read my [Project Notes](https://github.com/chauntelkellar/Apache-Load-Balancer/Project-Notes.MD)
