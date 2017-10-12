# SS2
There is an ESXi installed on the blade. That is the standard. Then installed Windows
10 client with 16 GB of RAM, 200 GB storage and an 8 cores processor. 
On the Win 10 Client there is a VMware Workstation and there I set up ESXi. Let's call it ESXi 2. 
There is 4GB og ram and 4 cores, but I will increase them for further machines. 
Next to the ESXi I already configured Windows Server 2012, and I will install the Vcenter here as well. 
Basically the whole SS2. They are on vmnet8 (NAT) I configured it. 
This is a good idea for those people who don't have 16 GB RAM, because they can't install Vcenter on their laptops with 8 GB. 
The only thing is I enabled native virtualization on the Windows 10 and everything works.
