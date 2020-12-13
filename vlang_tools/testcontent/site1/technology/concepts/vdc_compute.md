# VDC Compute 

![](img/evdc_compute.png)

## What is Hercules Compute?

VDC Compute is a container management & deployment platform. It presents a 1 click deployment solution for a full decentralized Kubernetes environment.  *Every* 3node on the TF Grid is able to run these containers and/or master and worker nodes.  This presents the advantage that edge based 3nodes and  core data based 3nodes centers create a distributed platform of nodes providing full scaleout capabilities to solutions. 

VDC Compute uses the ThreeFold capacity layer build by hardware and Zero-OS and is orchestrated buy your virtual system administrator called 3bot.

## Features

*   It is 100% compatible with Kubernetes & docker (market std)
*   It has full integration with Zero-OS overlay networking layer (efficient, ultra secure (encrypted) network between the containers)
*   Deploying it is easy at the edge and central datacenter locations
*   It can be integrated with scalable & capable monitoring systems (prometheus based). Monitoring agent deployed by default in the containers and kubernetes nodes
*   It can be integrated with our advanced billing/charge back mechanism
*   Very secure because it uses a strict single-tenant policy!

## Main Benefits

*   [Hercules Protect](zos_protect): no hacking surface to the Zero-Nodes, integrated silicon route of trust
*   [Hercules P2P Network](vdc_network): encrypted private overlay network connects all *N* containers to all other *(N-1)* containers.  Consider it to be your Virtual Private Datacenter.
*   [planetary network](planetary_network): a true global single backplane network connecting us all
*   [ZOS Filesystem ](zos_filesystem) (v2.x): A filesystem that has built in deduplication facilities , creates a zero-install environment for applications and is hacker-proof for use in containers on kubernetes
*   [Hercules Web Gateway](web_gateway): intelligent connection between web (internet) and container services.  By default your private virtual (overlay) network is not connected tot he public internet.  You have to design the network to be connected to the public internet through a web gateway.  This web gateway can exist anywhere on the TF Grid.

!!!include:usp_sustainable
!!!include:usp_manageable
!!!include:usp_scalable
!!!include:usp_reliable_secure

## Roadmap

### v2.1: Active

*   Integrated with our grid based 3bot solution: interactive workflows for deployment/upgrade/troubleshooting (chatbots in jumpscale) 
*   Custom logging: Zero-OS Alerts & Logs to a memory database of choice for customer (redis, at a location at choice of the customer).
*   Statistics aggregated in memory database of choice for customer (redis, at a location at choice of the customer).
*   Super fast boot time: the use of our ultra-efficient virtual filesystem allows boot in seconds without downloading of docker images (v1.2).
*   Edge cloud efficient virtual filesystem: deduped virtual filesystem leads to huge space & bandwidth savings
*   Hacker proof launch of files: each file started get's compared against a secure hash making sure only the pre-defined files can be launched in a container
*   redundancy for Kubernetes controller


### v2.x: OEM (on request by larger customers)

*   [Hercules Virtual Disk integration](hercules_disk)
