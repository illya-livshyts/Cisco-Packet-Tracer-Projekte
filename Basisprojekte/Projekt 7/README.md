# Projekt 7: VLANs über 2 Access Switches mit zentralem Multilayer Switch
## 🖥️ Geräte
4 PCs

2 Switches 

1 Multilayer Switch

 
## Ziel:
Zwei VLANs über zwei Access Switches hinweg verbinden. Dabei übernimmt ein zentraler Multilayer Switch das Routing zwischen den VLANs.



## ⚙️Schritt-für-Schritt-Anleitung:

1) Verkabelung:

PC0 → Switch0 (VLAN 2)

PC1 → Switch0 (VLAN 3)

PC2 → Switch1 (VLAN 2)

PC3 → Switch1 (VLAN 3)

Switch0 ↔ Multilayer Switch (Trunk)

Switch1 ↔ Multilayer Switch (Trunk)


2) VLANs erstellen:

VLAN 2

VLAN 3        
(Auf beiden Access Switches und dem Multilayer Switch)

3) Ports den VLANs zuweisen:

Fa0/1 von PC0 → VLAN 2

Fa0/2 von PC1 → VLAN 3

Fa0/1 von PC2 → VLAN 2

Fa0/2 von PC3 → VLAN 3

4) Trunk-Ports konfigurieren:

-Verbindung von jedem Access Switch zum Multilayer Switch → Trunk-Modus

-Damit VLANs über den Link transportiert werden können


5) SVIs auf dem Multilayer Switch erstellen (für Routing):

VLAN 2: IP 2.2.2.1   255.255.255.0

VLAN 3: IP 3.3.3.1   255.255.255.0

6) PCs konfigurieren:

PC0 → 2.2.2.2, Gateway: 2.2.2.1

PC1 → 3.3.3.2, Gateway: 3.3.3.1

PC2 → 2.2.2.3, Gateway: 2.2.2.1

PC3 → 3.3.3.3, Gateway: 3.3.3.1

7) IP-Routing aktivieren auf dem Multilayer Switch   

8) Test der Konnektivität:

Ping von PC0 ↔ PC2 (gleiches VLAN)

Ping von PC1 ↔ PC3 (gleiches VLAN)

Ping zwischen PC0 ↔ PC1 (zwischen VLANs)

## 📚 Erklärung:
Dieses Projekt bildet eine klassische VLAN-Struktur mit zentralem Routing über einen Multilayer Switch nach. Die Access Switches leiten VLAN-Daten per Trunk an den zentralen Switch weiter, der das Routing übernimmt. So können alle Geräte – auch wenn sie an verschiedenen Switches hängen – miteinander kommunizieren, sofern es erlaubt ist.



## 📎 Anhang:
Screenshots zu diesem Projekt befinden sich im Anhang
