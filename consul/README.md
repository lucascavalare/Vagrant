- Vagrantfile will start three virtual machines.
  - One will act as a Consul serve and the other two will act as Docker hosts. 
  
  - Setup is as follow:
    - `consul-server`, the Consul server node based on Ubuntu 18.04, has IP `192.168.33.10`.
    - `net-1`, the first Docker host based on Ubuntu 18.10, has IP `192.168.33.11`.
    - `net-2`, the second Docker host based on Ubunut 18.10, has IP `192.168.33.12`.

    ![networkDiagram](https://user-images.githubusercontent.com/19478719/76568451-c758f280-64a8-11ea-98f6-a5142862a8c3.jpg)
