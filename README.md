# Networkwalks-B084k-Extra-project-of-Week1-Setup-Window-10-in-Virtual-Box-
Cybersecurity Lab setup Week 1
Lab Documentation: Windows 10 & Kali Linux NAT Network Integration
Task Overview & Objective:Set up a Windows 10 virtual machine inside Oracle VirtualBox and connected it to the same NAT network as the Kali Linux VM.
Confirmed that both machines can reach each other and establish smooth peer-to-peer communication.
Virtual Machine Configuration (Windows 10):
Created a new virtual machine in VirtualBox named Windows10-Lab.
Assigned Microsoft Windows (64-bit) as the OS type, 4096 MB (4 GB) of RAM, and a VDI dynamically allocated hard disk of at least 40 GB.
Attach the ISO and Start Install:
Navigated to Settings > Storage, clicked the empty disk icon under the controller, and chose the downloaded Windows 10 ISO file.
Started the VM, proceeded through the Windows setup, selected Custom Install, chose the virtual disk, and let the installation complete.
Set the Network to NAT Network:
Accessed Settings > Network on the VM.
Attached the network adapter to NAT Network and selected the exact same NAT Network name used by the Kali Linux VM.
Set a Static IP inside Windows:
Opened Control Panel > Network and Sharing Center > Change adapter settings.
Accessed the network adapter properties, opened Internet Protocol Version 4 (TCP/IPv4) properties, and configured the custom static address.
Test Connectivity:
Opened Command Prompt on Windows and verified connectivity to the Kali VM and external network access.
Confirmed bidirectional communication and successful ping testing with 0% packet loss.
