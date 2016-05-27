# RVIServerMasterOS
This repository is for RumahVoIP Server Master Operating System/RumahVoIP Node Server - [http://rumahvoip.or.id](http://rumahvoip.or.id) 

##Server Specification
CentOS 7 x64 bit with SELinux and Firewall disabled ( You can customize with yourself) and you can import RumahVoIP.ova/RumahVoIP.vhd to your virtual machine

##Installed Package
- Asterisk 13
- Chan_dongle 
	( Need to be testing for asterisk13, module unloaded. You need to edit /etc/asterisk/dongle.conf first before you use )
- Asterisk Addons
- Mariadb 5.5.44
- A2billing
- A2billing integration
- "Development Tools"
- LAMP
- Mod Security (Web Application Firewalls & Intrusion Detection System)
- Mod Evasive( DDoS Protection)
- Iksemel (Google Voice Dependencies)
- Dahdi (If you want to use PSTN)
- FreePBX 13
- PJSIP (disabled)
- SIP
- jansson
- pjproject
- G722 (High Definition 'Wideband') audio
- Lame(MP3)
- FFmpeg
- OpenLDAP ( for OpenFire etc)
- Fusion Directory( for LDAP Administration)
- OpenFire 4.0.2
- Ejabberd (Need to Configure hostname first)
- Erlang
- ImageMagick
- GhostScript
- Perl-* Package
- PPTP
	 ( Not Configured : https://www.photonvps.com/billing/knowledgebase.php?action=displayarticle&id=58 )
- L2TP 
	( Not Configured : https://github.com/travislee8964/L2TP-VPN-installation-script-for-CentOS-7/raw/master/l2tp-ipsec-install-script-for-centos7.sh )
- OpenVPN
	 ( Not Configured : https://www.digitalocean.com/community/tutorials/how-to-setup-and-configure-an-openvpn-server-on-centos-7 )

##FreePBX Module
- Backup & Restore
- Blacklist
- Bulk Handler
- CallerID Lookup
- Certificate Manager
- Contact Manager
- Digium Addons
- Soung Language
- Call Flow Control
- Call Forward
- Call Recording
- Call Waiting
- Do-Not-Disturb (DND)
- Info Services
- Voicemail Blasting
- Digium Phones Config
- SMS
- Weak Password Detection
- Call Event Logging
- Asterisk Logfiles
- Asterisk Info
- CDR Reports
- Voicemail
- Music on Hold
- User Management 

##Download Link
It will be published soon... (Need to be testing and create a documentation)

##Important Notes
We don't publish credential information about this server. After you download the .ova/.vhd file, you must send request about password and other credential information to **dev@rumahvoip.or.id**

##Documentations
In Progress...

##How to Contribute or join RumahVoIP
Just use this Telegram invite link to join Telegram RumahVoIP Group https://telegram.me/joinchat/Aj-3SAH5Omc2U_klOv7l0A
