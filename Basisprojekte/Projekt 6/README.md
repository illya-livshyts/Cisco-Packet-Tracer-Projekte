# Projekt 6: VLANs auf einem Multilayer Switch (Layer 3)

## Projektziel
Verbindung zwischen 3 PCs über einen Multilayer Switch mit VLANs. Jeder PC befindet sich in einem eigenen VLAN mit jeweils eigener IP-Adressierung.




### 🖥️Geräte

3x PCs	   
1x Multilayer-Switch	    
3x Kupferkabel (Straight-Through)


## 🖧 Netzwerkaufbau
Verbindungsschema:    
PC0 ↔ Multilayer-Switch

PC1 ↔ Multilayer-Switch

PC2 ↔ Multilayer-Switch

Jeder PC ist mit einem eigenen Port des Multilayer-Switches verbunden.



## Schritte:
1) Aufbau:

Verbinde:

PC0 → Fa0/1 des Multilayer Switches

PC1 → Fa0/2

PC2 → Fa0/3

2) VLANs erstellen:

VLAN 2 für PC0

VLAN 3 für PC1

VLAN 4 für PC2

3) Ports VLANs zuweisen:

Fa0/1 → VLAN 2

Fa0/2 → VLAN 3

Fa0/3 → VLAN 4

4) SVIs (Switch Virtual Interfaces) konfigurieren:

VLAN 2 → IP: 2.2.2.1

VLAN 3 → IP: 3.3.3.1

VLAN 4 → IP: 4.4.4.1

5) PCs IP-Adressen zuweisen:

PC0: 2.2.2.2 / Gateway: 2.2.2.1

PC1: 3.3.3.2 / Gateway: 2.2.2.1

PC2: 4.4.4.2 / Gateway: 2.2.2.1


6) Inter-VLAN Routing aktivieren:

IP Routing am Multilayer Switch aktivieren.

7) Verbindung testen:

Pinge von jedem PC zu den anderen.

Alle Pings sollten erfolgreich sein





## 📝 Erklärung:
Dieses Projekt zeigt, wie ein Multilayer-Switch genutzt wird, um mehrere VLANs zu verwalten und das Routing zwischen ihnen zu ermöglichen. Jedes VLAN trennt den Datenverkehr logisch, aber durch den Layer-3-Switch kann Kommunikation zwischen den VLANs stattfinden – eine typische Konfiguration in modernen Netzwerken.
