# **Swarm compose**

A shell script to set up local cluster testing environment and initialise a new single master swarm locally.

## Installation and Setup Instructions

#### Prerequisites:  

`chmod +x swarm-compose`

#### Example:  

Starts the docker swarm nodes and create docker machines

`swarm-compose start`  

Delete all nodes and mahcines

`swarm-compose kill`  

Switch shell to master node

`swarm-compose eval`  