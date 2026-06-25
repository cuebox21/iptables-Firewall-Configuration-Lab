# iptables-Firewall-Configuration-Lab
This lab demonstrates hands-on Linux firewall configuration using iptables, the standard packet filtering framework in the Linux kernel. Working inside a fully virtualised multi-segment network (NETinVM on VMware Workstation Pro).
<h2>Platform Used</h2>
- <b>NETinVM (VMWare Workstation Pro)</b> 
<h2>Firewall OS</h2>
- <b>Linux (Debian 12 bookworm)</b>
- <h2>Tool Used</h2> 
- <b>iptables (Netfilter packet filtering framework) </b>

<h2>Screenshots:</h2>

<p align="center">
NETinVM desktop running inside VMware Workstation Pro <br/>
<img src="https://imgur.com/7UAYtIN.png" height="80%" width="80%"/>
<br />
<br />
NETinVM run script showing machine configuration  <br/>
<img src="https://imgur.com/UoatNpR.png" height="80%" width="80%">
<br />
<br />
Initial iptables filter table listing showing INPUT and FORWARD at DROP policy <br/>
<img src="https://imgur.com/KnSThCe.png" height="80%" width="80%">
<br />
<br />
Chain OUTPUT confirmed policy DROP after execution  <br/>
<img src="https://imgur.com/srBRTa2.png" height="80%" width="80%">
 <br />
<br />
Stateful rules applied silently across all three chains  <br/>
<img src="https://imgur.com/cWTgc1y.png" height="80%" width="80%">
<br />
<br />
Final complete rule set across filter and nat tables after all rules applied  <br/>
<img src="https://imgur.com/GsJuHug.png" height="80%" width="80%">
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
