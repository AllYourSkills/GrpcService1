﻿# GrpcService1

This is an example .Net C# service that provides a very basic grpc server wrapped with Docker and Nginx. 
It can be tested with any grpc client. [Bloom](https://github.com/uw-labs/bloomrpc) was used.  Within the Nginx directory localhost.crt and localhost.key are required. I also had to add the Root Certificate to Bloom. Grpc server runs on port 5000 with Nginx providing access via 80 or 443 
The basis for this used Tony Sneeds [Blog](https://blog.tonysneed.com/2019/10/13/enable-ssl-with-asp-net-core-using-nginx-and-docker/) That sets up SSL to between Nginx and a .Net Docker service.