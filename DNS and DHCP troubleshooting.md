DNS and DHCP Troubleshooting

Project Overview

This project documents my learning and practical exercises involving DNS, DHCP, and Windows network troubleshooting.

Lab Environment

* Server: Windows Server 2022
* Client: Windows 10
* Virtualisation: Oracle VirtualBox

What Is DNS?

DNS translates domain names into IP addresses so computers can locate servers and other network resources.

What Is DHCP?

DHCP automatically assigns network configuration, including IP addresses, subnet masks, default gateways, and DNS server addresses.

Troubleshooting Commands

1. Check IP Configuration

Command:
"ipconfig /all"

Purpose: Inspect the IP address, subnet mask, default gateway, DHCP server, and DNS server.

2. Test Network Connectivity

Command:
"ping 10.1.10.1"

Purpose: Test connectivity to the server at this address, if it matches the lab configuration.

3. Test DNS Resolution

Command:
"nslookup banele.local"

Purpose: Check whether DNS can resolve the domain name.

4. Renew the IP Address

Commands:
"ipconfig /release"

"ipconfig /renew"

Purpose: Request refreshed network configuration from DHCP. Use these commands on a suitable lab client.

Common Problems

* Incorrect IP configuration
* DHCP server unavailable
* Incorrect DNS server address
* DNS resolution failures
* Network connectivity problems

Learning Objectives

* Understand how DNS and DHCP support a Windows network.
* Practise basic network diagnostic commands.
* Identify possible causes of connectivity problems.
* Record troubleshooting steps and verified results.

Results

I will add the actual test results and solutions after completing each exercise in my home lab.
