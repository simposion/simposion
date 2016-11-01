# simposion
A distributed social network

## Purpose of this project
This project is created as a proof of concept of a completely distributed social network where every peson would host their own data and therefore read the updates of others directly from the sources. We plan to make client+server nodes and enable them to communicate via encrypted connection and to perform the discovery of others via a tracker, that is, a symulated DNS server where one can register their IP with a desired username and display their basic info like bio and location. This is a handy and the only centralised and optional part of the system that will keep track of the Dynamic IP addresses of the people with Dyn. IP. The system will include node clients, pieces of software that will be used to connect to the node securely so you can publish and use all of the possibilities of a node from a remote device souch as a PC or a Mobile Phone.
A HTTP JSON serving content serving can be also an optional node capability. Where a hosted page ona domain can display via AJAX someones content. The encryption should be RSA and then AES once two nodes befriend. And AES only between node and node clinet.

The functionality of this network should resemble Twitter in it's early stage: statuses, likes with comments but no reposts. The first node client will be written for the use in Terminal. More security concerning the length of the messages, anti brute force and anti spam mechanisms can be developed later.

All of the parties, meaning the nodes, node client for PC and the tracker (or maybe later the system of distributed trackers) will be written in python.

This project is meant to demonstrate the secure client-server communication and custom protocol development, a fun project that descrbes the innerworkings of the Internet, and maybe contributes to the topic of Distributed Web. After all our home routers are connected to the Internet 24/7. Why wouldnt we host out own content from a Raspberry Pi?
