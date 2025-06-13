# Projekt 8: Inter-VLAN Routing mit Router
## 🖥️Geräte:
1 Router 

1 Switch 

3 PCs


## Ziel:    
Drei VLANs werden über einen einzigen Switch eingerichtet. Der Router übernimmt das Inter-VLAN Routing über eine Subinterface-Konfiguration („Router-on-a-Stick“).

## Schritt-für-Schritt-Anleitung:
1) Verkabelung:          

PC0 → Switch0 (Fa0/1)

PC1 → Switch0 (Fa0/2)

PC2 → Switch0 (Fa0/3)

Switch0 (Fa0/4) → Router0 (Fa0/0)

2. VLANs auf dem Switch einrichten 
3. Ports den VLANs zuweisen 
4. Trunk-Port zum Router konfigurieren (Switch-Port)

5. Router-Konfiguration (Router-on-a-Stick)

6. PCs konfigurieren:    

PC0 → 192.168.2.2 / Gateway: 192.168.2.1

PC1 → 192.168.3.2 / Gateway: 192.168.3.1

PC2 → 192.168.4.2 / Gateway: 192.168.4.1


 7. Konnektivität testen:   

Ping zwischen allen PCs

Test, ob Routing über den Router funktioniert (zwischen VLANs)

## 📚 Erklärung:    
Hier wird mit dem klassischen „Router-on-a-Stick“-Prinzip gearbeitet. Der Switch übernimmt die VLAN-Zuweisung, während der Router mit Subinterfaces den Datenverkehr zwischen den VLANs routet.

Dies ist ein Grundkonzept in Netzwerken mit älterer Hardware oder in kleinen Netzwerken ohne Multilayer Switch.

## 📎 Anhang:
Screenshots zur Netzwerktopologie und Konfiguration befinden sich im Anhang
