configip.cs readme
*** Auther: Ugonna Iheanacho ***

This program will deliver network adapter and ip address information
Commands:
	configip -h, help, or ? to display help menu with other commands.
	configip /all to display full configuration information of network adapters (excluding loopback).
	configip to display basic configuration information of network adapters (excluding loopback).
	
	Default operation is configip, to display basic information.
	
Limitations **
	Program will not find the accurate IPRouting enabled value, instead it finds the number of routes available to that pc.
	Program will not find the lease obtained and lease expired may be off by certain hours.
	Program will not find the DHCPv6 IAID due to relative complexity and lack of supported code.
	Program will not find the DHCPv6 DUID due to relative complexity and lack of supported code.
	Program will not find the Netbios over Tcpip enabled value, alternatives were tried and could not work.
	
NOTE***
	If your network connection has a non dedicated NodeType (ex. Peer2Peer) some information may not be displayed.
	Lack of ability to test all network NodeTypes leads to the inability to cover all exceptions.