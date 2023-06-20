# Documentation for E05

## 1. The complete physical and logical drawing of topology with switches ,adaptors VLANS, routers etc

```
Physical Topology

	The topology diagram illustrates the detailed telecommunication network transmit
	data through wireless transmitters or cables.
 
 ```

* [physicaltopology](/E05/E05physicaltopology.drawio)

or 


![](/E05/physicaltopologyexe5.JPG)
	
```
Logical topology

IPv4 subnets & Addresses - OSI Model Layer 3 information
VLAN information (Where those subnets are used) - OSI Model Layer 2 information

```
* [logicaltopology](/E05/E05logicaltopology.drawio)

or 


![](/E05/logicaltopologyex5.JPG)


## 2. Configuration of all the network devices
 ```
 * Various configuration steps done on network devices at different stages and they are saved using the 
 command save
 * The configuration is written onto the hard disk of the network devices. 
 * The virtual machine devices will remember the configuration even after restarting/booting the virtual machine.
 * The configurations of all netwoork devices are saved and its details are in the following document.
 
  ```

* [Switch1](/E05/switch1.cfg)

* [Switch2](/E05/switch2.cfg)

* [Vyos](/E05/vyos.cfg)

* [Router2](/E05/router2.cfg)


## 3. command ip addr

```
 The operating system Ip-address is verified in the lubuntu 3 Qterminal using the command 
	ip addr
	the results are showed in the image.
```
![](/E05/lubuntu3_ipaddress.JPG)

## 4. Testing connectivity

``` Connectivity test  is verified using the command ping and traceroute.
	Depending on virtual machine terminal we are ping the opposing machine's IP-address.
	Both the machines connectivity is shown in the below images.
    All the network connectivity test is shown below.
```
```
Lubuntu 3 <-> Lubuntu 1

```
![](/E05/lubuntu3-1_ping%2Ctraceroute.JPG)

```
Lubuntu 3 <-> Lubuntu 2

```
![](/E05/lubuntu3-2_ping%2Ctraceroute.JPG)

```
 Lubuntu 3 <-> Vyos
 ```
 ![](/E05/lubunutu3-vyos_ping%2Ctraceroute.JPG)

```
  Lubuntu 3 <-> router2
 ```
 ![](/E05/lubunutu3-router2_ping%2Ctraceroute.JPG)

```
 Lubuntu 1 <-> router2

 ```
![](/E05/lubuntu1-router2_ping%2Ctraceroute.JPG)

 ```
 Lubuntu 2 <-> router2

 ```
![](/E05/lubuntu2-router2_ping%2Ctraceroute.JPG)
 

 ## 5. DHCP server leases

``` 
    verified the  show dhcp server leases -command from R1 & R2

```
![](/E05/vyos_dhcpserver.JPG)

![](/E05/router2_dhcpserver.JPG)


## 6. Static Routing screenshots

```
  below mentioned screen shots are the various steps followed during static route configure on vyos and router 2 and showing iproute
```

![](/E05/vyosrouter1_showiproute.JPG)


![](/E05/router2_showiproute.JPG)


![](/E05/router2_showiproute_2.JPG)
