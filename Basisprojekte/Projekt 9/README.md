# Projekt 9: VLAN-Kommunikation mit Multilayer-Switch, Router und Servern
## 🖥️Geräte:
1 Router 

1 Multilayer Switch 

3 Switches 

4 PCs

2 Server


## Ziel:
Ein großes Netzwerk mit mehreren VLANs, Servern und einem Router. Der Multilayer Switch übernimmt das Inter-VLAN Routing. Die Server befinden sich im VLAN 4, die Clients in VLAN 2 und 3. Der Router stellt die Verbindung zu einem externen Netzwerk (z. B. Internet ) über VLAN 5 her.

## Schritt-für-Schritt-Konfiguration:
1) VLANs definieren (am Multilayer Switch)

2) Zuweisung der Ports zu VLANs auf den Access Switches.
Dies wird auf allen Access Switches analog für die PCs gemacht

3) Verbindungen zum Multilayer Switch (Trunk konfigurieren)

4) Routing im Multilayer Switch aktivieren

5) SVIs (Switched Virtual Interfaces) konfigurieren am Multilayer Switch

6) Router konfigurieren (für Verbindung zu VLAN 5 / externem Netz)

7) PCs konfigurieren:   

PC3 (VLAN 2) → IP: 192.168.22.2, Gateway: 192.168.22.1

PC4 (VLAN 3) → IP: 192.168.33.2, Gateway: 192.168.33.1

PC5 (VLAN 2) → IP: 192.168.22.3, Gateway: 192.168.22.1

PC6 (VLAN 3) → IP: 192.168.33.3, Gateway: 192.168.33.1

8. Server konfigurieren:    

Server0 (VLAN 4) → IP: 192.168.44.2, Gateway: 192.168.44.1

Server1 (VLAN 4) → IP: 192.168.44.3, Gateway: 192.168.44.1


## 📚 Erklärung:
Dieses Projekt kombiniert mehrere wichtige Netzwerkfunktionen:

-VLAN-Trennung für logische Netzwerke

-Layer 3 Routing im Multilayer-Switch

-Verbindung zu einem externen Netzwerk (Internet oder DMZ) über einen Router

-Serverbereitstellung für verschiedene VLANs

-Ein solches Setup ist typisch für echte Unternehmensnetzwerke.

### 📎 Anhang:
Screenshots zur Topologie und Konfiguration befinden sich im Anhang
