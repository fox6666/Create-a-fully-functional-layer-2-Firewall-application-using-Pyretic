# Create-a-fully-functional-layer-2-Firewall-application-using-Pyretic
Advanced Computer Networking : progect 3

This is the project for the USTC course ：Advanced Computer Networking  
project 3：`Create a fully functional layer-2 Firewall application using Pyretic`

## Objective
  * Implement a layer 2 firewall that runs alongside the MAC learning module on the Pyretic runtime

## topology
<div align=center>
    <img width="759" height="300" src="https://github.com/fox6666/Datacenter-Network-Simulation-using-ns3/blob/master/image/network.png"       "网络拓扑图"/>
</div>

## Pyretic policies
 <div align=center>
    <img width="759" height="300" src="https://github.com/fox6666/Datacenter-Network-Simulation-using-ns3/blob/master/image/network.png"       "网络拓扑图"/>
</div>
  
## Firewall
 * `pyretic_firewall.py`: a skeleton class which you will update with the logic for installing firewall rules.
 * `firewall-policies.csv`:  a list of MAC pairs (i.e., rules) read as input by the firewall application. These pairs are the 
 　　　　　　　　　　　　hosts`can’t` communicate with each other.
 * You can provide the firewall rules in `firewall-policies.csv` and read it into the main function
 * Rules are decided by you!
 * These 2 files can be downloaded `on the course webpage`


