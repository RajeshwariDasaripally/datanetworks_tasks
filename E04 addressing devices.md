# Documentation for E04

## 1. The complete physical and logical drawing of topology with switches ,adaptors VLANS, routers etc

```
Physical Topology

	The topology diagram illustrates the detailed telecommunication network transmit
	data through wireless transmitters or cables.
 
 ```

* [physicaltopology](/E04/E04physicaltopology.drawio)
	
or 


![](/E04/physicaltopologyex4.JPG)

```
Logical topology

IPv4 subnets & Addresses - OSI Model Layer 3 information
VLAN information (Where those subnets are used) - OSI Model Layer 2 information

```
* [logicaltopology](/E04/E04logicaltopology.drawio)

or 


![](/E04/logicaltopologyex4.JPG)


## 2. Configuration of all the network devices
 ```
 * Various configuration steps done on network devices at different stages and they are saved using the 
 command save
 * The configuration is written onto the hard disk of the network devices. 
 * The virtual machine devices will remember the configuration even after restarting/booting the virtual machine.
 * The configurations of all netwoork devices are saved and its details are in the following document.
 
  ```

* [Switch1](/E04/switch1.cfg)

* [Switch2](/E04/switch2.cfg)

* [Vyos](/E04/vyos.cfg)

## 3. command ip addr

```
 The operating system Ip-address is verified in the lubuntu Qterminal using the command 
	ip addr
	the results are showed in the image.
```
![](/E04/lubuntu1and2ipaddress.JPG)

## 4. Testing connectivity

``` Connectivity test  is verified using the command ping.
	Depending on virtual machine terminal we are ping the opposing machine's IP-address.
	Both the machines connectivity is shown in the below images.
    All te network connectivity test is shown below.
```
```
Lubuntu <-> Lubuntu

```
![](/E04/lubuntu1pinglubuntu2.JPG)

```
 Lubuntu <-> Vyos
 ```
 ![](/E04/lubuntu1pingvyos.JPG)

```
 Lubuntu <-> Switch1

 ```
![](/E04/lubuntu1pingswitch1.JPG)

 ```
 Lubuntu <-> Switch2

 ```
![](/E04/lubuntu1pingswitch2.JPG)

 

 ## 5. show interfaces

``` 
    verified the settings taken into use by show interfaces

```
![](/E04/vyos_showinterface.JPG)


 ## 6. show ip route
```
checked the routing table with show ip route for connected networks (letter C infront of the row).

```
![](/E04/vyos_showiproute.JPG)
