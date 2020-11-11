
# Linux-Tasks
Linux Projects/Tasks

Task-1: Dual Booting Linux(RHEL or CentOS) and Windows Server with ( GPT and MBR ),Installing Linux with minimal (no GUI).
Task-2: Installation: minimal, Installation using GPT
Task-3: Configure your base machine as “Yum Server".
Task-4: Install GNOME
Task-5: Install KVM / Virtual Machine Manager
Task-6: Create the following Guest OS:
            Each Guest should have 2 storage
                       HDD1: 20G, HDD2: 10G
                RAM: Depending on the Guest
                      CPU: 1 Core
              pc1.kochi.ibm.com : CentOS7.1
              pc2.kochi.ibm.com : CentOS7.1
              pc3.kochi.ibm.com : RHEL7
              pc4.kochi.ibm.com : Ubuntu
              pc5.kochi.ibm.com : Windows
Task-7: Assign IP address manually on base machine, pc1, pc2, pc3 in the range: 172.20.10.0/24
Task-8: pc4, pc5 should get address from DHCP server, Therefore, Configure PC1 as DHCP Server
Task-9: Check whether VM’s / Guest are able to communicate with Host or Base PC
Task-10: Configure base machine as YUM server, so that pc1, pc2, pc3 can download package from pc1, Check whether you can install packages on pc1, pc2, pc3.
Task-11: Configure pc2 as DNS Server, Install using “BIND” package, Optional (Configure a PC2 as Master & PC3 as Slave DNS Server).
Task-12: Check whether the BaseOS, VM’s can be remote accessed from other PC, mobile using SSH, VNC.
Task-13: Configure PC1 as Web Server and File Server
Share File’s using File Server and check whether from client you are able to upload and download files
                      
                      
                      
                      For FTP: Configure vsftpd/ sftp  Jailed if possible, Access via Filezilla
                      For Web server: Configure apache → Access using browser
Task-14: Configure pc4 as Nagios/Zabbix server, Using Nagios/Zabbix server, monitor other PC’, monitor the load, CPU, Memory utilization of OS, web server, DNS Server and other PC’s.
Task-15: Add 2 new hard disk on pc1 (VM), Configure RAID (Redundant Array of Inexpensive Disks).
