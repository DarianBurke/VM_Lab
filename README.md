<h1>Virtual Machine Home Lab</h1>


<h2>Description</h2>
This project demonstrates a simple virtual networking lab using two Windows 11 virtual machines configured in Oracle VirtualBox. The goal was to establish communication between the VMs using Host-Only networking (Adapter 2), allowing isolated network testing without external internet access.

During the setup, I encountered and resolved IP address configuration issues by using the netsh command-line tool to manually assign and troubleshoot network settings.
<br />


#### 🔧 Languages and Utilities Used
- **Operating System:** Windows 11  
- **Virtualization Platform:** Oracle VirtualBox  
- **Command-Line Tools:** netsh, Command Prompt (CMD)  
- **Networking:** Host-Only Adapter configuration, IP addressing  

#### 💡 Skills Demonstrated
- Virtual network setup and configuration  
- Troubleshooting connectivity and IP issues  
- Using Windows networking commands for system management  
- Understanding of host-only and isolated network environments  


<h2>Program walk-through:</h2>

<p align="center">
Creating VMs using Oracle VirtualBox <br/>
Initial Set-Up: <br/>
<img src="https://i.imgur.com/69q3mGt.png" height="80%" width="80%" alt="Initial setup"/>
<br />


<p align="center">
VM Settings Configuration: <br/>
<img src="https://i.imgur.com/lOHggG5.png" height="80%" width="80%" alt="VM Settings Configuration"/>
<br />


<p align="center">
Both Windows 11 VMs Created: <br/>
<img src="https://i.imgur.com/tc2yAng.png" height="80%" width="80%" alt="Both Windows 11 VMs Created"/>
<br />


<p align="center">
Inbound Rules and ICMP Configuration: <br/>
<img src="https://i.imgur.com/X89CsUe.png" height="80%" width="80%" alt="Both Windows 11 VMs Created"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
