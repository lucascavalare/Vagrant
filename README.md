# [Vagrant](https://www.vagrantup.com/)
  
  * **GRE Tunnel**
    - Building GRE Tunnel between Docker Hosts.
      - GRE to encapsulate IPv4 traffic and provide route between containers using their private addresses.
      
      - To showcase:
        - Host 1: 192.168.33.11
        - docker0 bridge: 172.17.0.1
        - GRE Tunnel Endpoint: 172.17.0.2
        - Docker Containers: 172.17.0.0/17
        
        - Host 2: 192.168.33.12
        - docker0 bridge: 172.17.128.1
        - GRE Tunnel Endpoint: 172.17.128.2
        - Docker Containers: 172.17.128.0/17
      
        - Splitting a/16 Network in TWO /17 Networks and assign each subnet to the two different hosts ensures that containers 
          won't get conflicting IP Addresses.
          
      - Each host has the latest stable version of Docker and two network interfaces: one NAT interface that gives outbound           connectivity and one interface on a private network.
     
