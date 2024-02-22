# Net-Lab-2024
Network+ Lab @ Divergence FEB2024

## STAGE 1 - Starting of the Network: 

Built out the network infrastructure for the small business environment.  First, I add new devices ot the workspace and linked them up.  Then configured the LAN network on the firewall through the CLI over th console interface.  Next, I added a WIN10 workstation to the LAN network, and then connected to the firewall GUI form the WIN10 workstation. 
Lastly, I completed the network setup throught the firewall GUI.  Built the networks on the FortiNet firewall (FortiGate).

![Network+ Stage 1A](https://github.com/agardiner17/Net-Lab-2024/assets/160628597/b80347d2-6919-4483-a403-9995771ed78a)


## STAGE 2 - Domain Setup:

Built Windows domain for the small business environment by adding devices to the workspace and linked them up.  Prepared a WIN2012r2 server for the "Active Directory Domain Service" server role.  Then installed the "Active Directory Domain Services" server role.  Next, I created a new Admin user accounts.  Then prepared WIN10 to join the domain.  WIN10 joined to the widgets.localdomain.domain.  Lastly, set the desktop background on WIN10 with group policy from the DC.

![Network+ Stage 2B (2)](https://github.com/agardiner17/Net-Lab-2024/assets/160628597/09d0c395-f4de-41df-a6b4-830cfe594f24)

## STAGE 3 - IIS Setup:

Built a IIS server on a Win2012r2 server, and joined the server to the domain, by adding new devices to the workspace and linked them up.  Then prepared WIN2012r2 server to join the domain.  Next, I installed the "Internet Information Services" server role.  Lastly, I added a test webpage, and verified access over the LAN network.

![Network+ Stage 3B](https://github.com/agardiner17/Net-Lab-2024/assets/160628597/2637b70b-f2a3-4354-8588-25168dba4da5)

## STAGE 4 - LAMP Setup:

Built a LAMP webserver onto the Ubuntu server on the DMZ network, by adding new devices to the workspace and linked them up.  I prepared the Ubuntu server and then installed DokuWiki.  Next, I configured DokuWiki.  Lastly, I setup a VIP for the public side of the webserver on the firewall.  

![Network+ Stage 4A](https://github.com/agardiner17/Net-Lab-2024/assets/160628597/a3549aca-2ed7-4160-a907-421d5acbdd73)

## STAGE 5 - FTP Setup:

Built a FTP server on a Win2012r2 server to the DMZ workspace, by adding new devices to the workspace and linked them up.  Then I prepared the WIN2012r2 server and installed the FTP service. 

![Network+ Lab Stage 5](https://github.com/agardiner17/Net-Lab-2024/assets/160628597/56d15e5c-c598-4325-b680-0df35547b6ad)

## STAGE 6 - Hardening The Environment:

Research of hardening for the Widgets environment:

Finding documentation from vendors and other industry sources on hardening, and added it to the wiki. 

# THE WRAP UP:
### THE NETWORK BUILT:

A SMB (small/medium business) netowrk, with a LAN, DMZ, and Guest Network.
- A Windows domain environment.
- A Windows FTP server.
- A Win10 workstation.

A LAMP webserver running on Ubuntu, hosting a wiki.

A FortiGate firewall, with a VIP for a DMZ webserver. 










