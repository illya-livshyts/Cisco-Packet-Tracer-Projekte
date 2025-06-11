# Projekt 2: Verbindung über einen Switch

Alle vier PCs über einen Switch miteinander verbinden, IP-Adressen zuweisen und die Kommunikation im Netzwerk testen.

🖥️ Geräte: 4 PCs, 1 Switch, 4 Straight-Through-Kabel

## Schritte:
1.Geräte platzieren:   
Ziehe 4 PCs und 1 Switch auf die Arbeitsfläche in Cisco Packet Tracer.

2.Verkabelung:  
Verbinde jeden PC mit dem Switch über ein Straight-Through-Kabel:

PC0 → Switch Port FastEthernet0/1

PC1 → Switch Port FastEthernet0/2

PC2 → Switch Port FastEthernet0/3

PC3 → Switch Port FastEthernet0/4

3.IP-Adressen zuweisen:  
Weise jedem PC eine eindeutige IP-Adresse im gleichen Subnetz zu:

| Gerät | IP-Adresse  | Subnetzmaske  |
| ----- | ----------- | ------------- |
| PC0   | 192.168.1.1 | 255.255.255.0 |
| PC1   | 192.168.1.2 | 255.255.255.0 |
| PC2   | 192.168.1.3 | 255.255.255.0 |
| PC3   | 192.168.1.4 | 255.255.255.0 |   
 


4.Switch konfigurieren:   
Für dieses einfache Setup ist keine Konfiguration nötig – der Switch arbeitet auf Layer 2 und leitet Frames automatisch weiter.

5.Verbindung testen:  
Auf einem beliebigen PC (z. B. PC0), öffne die Command Prompt

Pinge die anderen drei IP-Adressen an.


## 🧠 Erklärung:
In diesem Projekt habe ich vier PCs über einen Switch verbunden. Jeder PC hat eine eigene IP-Adresse im gleichen Subnetz bekommen. Der Switch braucht keine Konfiguration, da er automatisch Daten weiterleitet. Ich habe die Verbindung mit dem ping-Befehl getestet, und alle Pakete wurden erfolgreich übertragen. Dieses Projekt zeigt, wie einfache LAN-Verbindungen mit einem Switch funktionieren.


### 📎 Anhang:
Im Anhang befinden sich Screenshots zu diesem Projekt
