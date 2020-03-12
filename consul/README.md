- Vagrantfile will start three virtual machines.
  - One will act as a Consul serve and the other two will act as Docker hosts. 
  
  - Setup is as follow:
    - `consul-server`, the Consul server node based on Ubuntu 18.04, has IP `192.168.33.10`.
    - `net-1`, the first Docker host based on Ubuntu 18.10, has IP `192.168.33.11`.
    - `net-2`, the second Docker host based on Ubunut 18.10, has IP `192.168.33.12`.

    <img width="1134" alt="networkDiagram" src="https://user-images.githubusercontent.com/19478719/76568770-7c8baa80-64a9-11ea-93da-7c82da42c874.png">
