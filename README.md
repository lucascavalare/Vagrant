# [Vagrant](https://www.vagrantup.com/)
  
**GRE Tunnel**
  - Building GRE Tunnel between Docker Hosts.
  - GRE to encapsulate IPv4 traffic and provide route between containers using their private addresses.
      
**Flannel**
  - Creating an Overlay Newtwork for containers. 
  - Containers on different hosts can do communicate with each other without port mapping. 

**Consul**
  - Docker Network relies on Consul for Key-Value stores. 
  - Use Docker Network feature and a `VXLAN Overlay`. 
