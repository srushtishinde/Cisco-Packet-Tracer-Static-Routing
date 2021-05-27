Check out this link to download Cisco Packet Tracer files for Static Routing using 1 , 2 and 3 Routers respectively. 
https://github.com/srushtishinde/Cisco-Packet-Tracer-Static-Routing

# Cisco-Packet-Tracer-Static-Routing
Check the files to find the cisco packet tracer for static routing.
All the configurations and connections with labels are made in the above attached files of packet tracer. 
All you need to do is save these files and test for the transmission of packets between PCs. 
To test you configurations for static routing kindly use only 'Simple PDU' packets for transmission. 
**Note: (Important) When you send the Simple PDU packet from one PC to any another PC. The very first transmission highly likely to fail. 
After that, send another Simple PDU packet from the same route or from the same source PC to destination PC. The transmission will be successful.
You might need to send the packet at the most twice for the transmission to be successful. If the transmission still fails, it means that the configurations you have made are incorrect.***
If your transmission is successful between 2 PCs, it explains that the configurations and connections made are correct and your network configuration is ready. 




For additional information on Static Routing, refer the steps given for Static routing
Router Configuration:

1.Reboot Router 0 by powering OFF and ON under the physical tab.

2.Router performs the Power ON Self-Test (POST).

3.Click on ‘Config’ tab and then choose one of the interface for configuration. Provide appropriate IP address and subnet mask.

4.Proceed similarly for all other interfaces in use.

5.To update the routing table of ‘Router 0’ follow these steps, (a).Identify magnifying glass icon available at the vertical right pane of the packet tracer. Click the magnifying glass on to Router 0 and select the routing table from the drop down list. A routing table for Router 0 will be displayed having 2 entries typed as C (connected) with next hop field blank. (b).The routing table is to be updated with the next hop entry, so that the Simple PDU could be send on to the other network. Provide following entries in the routing table: Network Address, Subnet mask, Next Hop. 

6.Configure all the end devices by providing them IP address, subnet mask and the default gateway address. 

7.Test your network by sending simple PDU’s or pinging the computers from one network to other network. 

*****Router Configuration details for Static Routing Using 1 Router.*****

Sr. No. 	Network Device 	        Configuration (IP address, subnet mask, default gateway addr)

1	        Generic Router 0	Interface: FastEthernet 0/0
                                        
                                        IP address: 192.168.1.1
                                        
                                        Subnet address: 255.255.255.0
		                        
                                        Interface: FastEthernet 1/0
                                        
                                        IP address: 192.168.2.1
                                        
                                        Subnet address: 255.255.255.0

2	        PC0	                IP Address: 192.168.1.2
                                        
                                        Subnet address: 255.255.255.0
                                        
                                        default gateway: 192.168.1.1

3	        PC1	                IP Address: 192.168.1.3
                                        
                                        Subnet address: 255.255.255.0
                                        
                                        default gateway: 192.168.1.1

4	        PC2	                IP Address: 192.168.2.2
                                        
                                        Subnet address: 255.255.255.0
                                        
                                        default gateway: 192.168.2.1

5	        PC3	                IP Address: 192.168.2.3
                                        
                                        Subnet address: 255.255.255.0
                                        
                                        default gateway: 192.168.2.1

*****Router Configuration for Static Routing using 2 Routers*****

Sr. No. 	Network Device 	        Configuration (IP address, subnet mask, default gateway addr)

1	        Generic Router 0	Interface: Fast Ethernet 0/0
                                        
                                        IP address:192.168.1.1
                                        
                                        Subnet address: 255.255.255.0
		                        
                                        Interface: serial 2/0
                                        
                                        IP address:192.168.3.1
                                        
                                        Subnet address: 255.255.255.0
		                        
                                        Static Routing Table 
                                        
                                        Network: 192.168.2.0
                                        
                                        Mask: 255.255.255.0
                                        
                                        Next Hop: 192.168.3.2

2	        Generic Router 1	Interface: Fast Ethernet 0/0

                                        IP address:192.168.2.1
                                        
                                        Subnet address: 255.255.255.0
		                        
                                        Interface: serial 2/0
                                        
                                        IP address:192.168.3.2
                                        
                                        Subnet address: 255.255.255.0
		                        
                                        Static Routing Table 
                                        
                                        Network: 192.168.1.0
                                        
                                        Mask: 255.255.255.0
                                        
                                        Next Hop: 192.168.3.1


You can try router congirurations for static routing using three routers for self learning! 

Check the uploaded images for proper reference! 
