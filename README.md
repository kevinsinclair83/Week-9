# Week-9
## Honeypot Attack 1 ![Attack](https://github.com/kevinsinclair83/Week-9/blob/master/Week9HoneypotAttack.gif)
## Honeypot Attack 2 ![Attack](https://github.com/kevinsinclair83/Week-9/blob/master/Week9HoneypotAttack2.gif)


3 Honeypots deployed: 
honeypot1-dionaea 35.202.179.68
Dionaea is "meant to be a nepenthes successor, embedding python as scripting language, using libemu to detect shellcodes, supporting ipv6 and tls."

honeypot2-snort 35.192.153.234
Snort is an "open source intrusion prevention system capable of real-time traffic analysis and packet logging."

honeypot3-suricata 35.185.60.35 
Suricata is "capable of real time intrusion detection (IDS), inline intrusion prevention (IPS), network security monitoring (NSM) and offline pcap processing."

Issues encountered: Initially had issues generating honeypot attacks as the firewall rules were not configured correctly to make the VM's accesible through SSH. After correct configuration the honeypots showed thousands of attacks in a matter of days from various IP's originating from China, France, Germany, Korea, etc.  

A summary of the data collected:  ET DROP Dshield Block Listed Source group 1, 	ET CINS Active Threat Intelligence Poor Reputation IP TCP group 97, GPL SNMP public access udp...  

number of attacks: 4,974 

number of malware samples: 1,686 

