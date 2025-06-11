# Projekt 4: VLANs mit 2 Switches (8 PCs)


In diesem Projekt wurden zwei VLANs auf zwei Switches konfiguriert. Jeder VLAN enthält vier PCs (zwei pro Switch). Es wird gezeigt, wie VLANs über mehrere Switches hinweg funktionieren können und wie Geräte innerhalb desselben VLANs kommunizieren, auch wenn sie physisch an verschiedenen Switches angeschlossen sind.

---

## 🖥️Geräte

- 8 PCs (PC0–PC7)
- 2 Switches (Switch0, Switch1)
- 8 Straight-Through-Kabel
- 1 Straight-Through-Kabel (GigabitEthernet Trunk Switch0 ↔ Switch1)

## 🌐 IP-Adressierung
| Gerät | VLAN | IP-Adresse   | Subnetzmaske |
| ----- | ---- | ------------ | -------------|
| PC0   | 20   | 192.168.2.1 | 255.255.255.0 |
| PC1   | 20   | 192.168.2.2 | 255.255.255.0 |
| PC4   | 20   | 192.168.2.3 | 255.255.255.0 |
| PC5   | 20   | 192.168.2.4 | 255.255.255.0 |
| PC2   | 30   | 192.168.3.1 | 255.255.255.0 |
| PC3   | 30   | 192.168.3.2 | 255.255.255.0 |
| PC6   | 30   | 192.168.3.3 | 255.255.255.0 |
| PC7   | 30   | 192.168.3.4 | 255.255.255.0 |


 
### Switches verbinden:
Die beiden Switches wurden über die Gigabit-Ports (Gig0/1) verbunden.

Die Verbindung wurde als Trunk-Link eingestellt, damit sie Daten aus mehreren VLANs gleichzeitig übertragen kann.


## 🧠 Erklärung
Ein VLAN (Virtual LAN) ist ein logisches Netzwerk, das unabhängig von der physischen Struktur arbeitet. In diesem Projekt wurden zwei VLANs konfiguriert. Die Switches wurden über einen Gigabit-Trunk verbunden, um VLAN-Daten zwischen den Switches zu übertragen.

Die Trunk-Ports (gig0/1) übertragen VLAN-Informationen für mehrere VLANs gleichzeitig.

Die PCs kommunizieren nur innerhalb ihres VLANs, da kein Router vorhanden ist.

VLAN-Isolierung sorgt für mehr Sicherheit und eine bessere Netzsegmentierung. 


### 📎 Anhang:
Im Anhang befinden sich Screenshots zu diesem Projekt 
