# Projekt 13 – DHCP im VLAN mit zentralem Server                

In diesem Projekt wurde ein Netzwerk mit mehreren VLANs aufgebaut, bei dem ein zentraler DHCP-Server im VLAN 4 alle Clients in VLAN 2 und VLAN 3 automatisch mit IP-Adressen versorgt. Die VLANs sind logisch getrennt, aber durch Inter-VLAN-Routing auf dem Router miteinander verbunden. Jeder PC erhält eine IP-Adresse dynamisch per DHCP, statt manuell konfiguriert zu werden.




## Ziel des Projekts:
- Automatische Vergabe von IP-Adressen an Clients in VLAN 2 und VLAN 3.
- VLANs sind durch Inter-VLAN-Routing über einen Router verbunden



## 🖥️Geräte
Switch 1       
Router 1     
PCs     4         
Server  1   


##  Konfiguration DHCP/Router/Switch 

siehe im 📎 Anhang ! 



## 🌐 Warum 8.8.8.8 als DNS-Server?
Die Adresse 8.8.8.8 ist ein öffentlicher DNS-Server von Google. Er hilft dabei, Domainnamen wie www.google.com in IP-Adressen umzuwandeln. Ohne DNS müssten Benutzer IPs direkt eingeben, was unpraktisch ist. Deshalb wurde er im DHCP-Profil als Standard-DNS-Server eingetragen.


## 📎 Anhang
Screenshots zur Topologie und Konfiguration befinden sich im Anhang
