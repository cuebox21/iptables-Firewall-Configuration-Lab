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
Registry Explorer: SAM hive showing all user accounts including 'informant'  <br/>
<img src="https://imgur.com/eY71cHg.png" height="80%" width="80%">
<br />
<br />
DB Browser for SQLite: Chrome History query showing browsing activity including data leakage searches on March 23, 2015 <br/>
<img src="https://imgur.com/O6jiW8v.png" height="80%" width="80%">
<br />
<br />
Registry Explorer: NTUSER.DAT RecentDocs showing secret_project files and resignation letter accessed by the suspect:  <br/>
<img src="https://imgur.com/RAqWqmM.png" height="80%" width="80%">
 <br />
<br />
 FTK Imager: Google Drive user_default folder showing snapshot.db and sync_config.db wiped (null byte contents confirmed in hex panel)  <br/>
<img src="https://imgur.com/Y4LmOt8.png" height="80%" width="80%">
<br />
<br />
FTK Imager: FTK Imager: RM#1 exFAT partition showing Secret Project Data folder with hex panel confirming 'Authorized USB' volume label string  <br/>
<img src="https://imgur.com/S2Bo1kz.png" height="80%" width="80%">
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
