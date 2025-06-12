# Projekt 4: Einführung in VLANs (ohne Router)        

## Ziel:
-Zwei VLANs auf einem Switch einrichten

-Jedem VLAN zwei PCs zuweisen

-Kommunikation nur innerhalb des VLANs erlauben


#### 🖥️ Geräte:
4 PCs (2 pro VLAN)

1 Switch

4 Straight-Through-Kabel

## Schritte:
1.Topologie aufbauen:  
PC0 → Switch Port Fa0/1

PC1 → Switch Port Fa0/2

PC2 → Switch Port Fa0/3

PC3 → Switch Port Fa0/4    

2.IP-Adressen vergeben:
| Gerät | IP-Adresse   | Subnetzmaske  | VLAN    |
| ----- | ------------ | ------------- | ------- |
| PC0   | 192.168.2.1 | 255.255.255.0 | VLAN 2   |
| PC1   | 192.168.2.2 | 255.255.255.0 | VLAN 2   |
| PC2   | 192.168.3.1 | 255.255.255.0 | VLAN 3   |
| PC3   | 192.168.3.2 | 255.255.255.0 | VLAN 3   |


3.Switch konfigurieren

4.Kommunikation testen:  
PC0 → ping PC1 ✅ funktioniert (gleicher VLAN)

PC0 → ping PC2 oder PC3 ❌ funktioniert nicht (anderes VLAN, kein Router)


## 🧠 Erklärung:
In diesem Projekt habe ich zwei VLANs auf einem Switch eingerichtet: VLAN 20 und VLAN 30. Jeder VLAN wurde zwei PCs zugewiesen. Durch VLANs kann man Netzwerke logisch trennen, auch wenn alle Geräte physisch an demselben Switch hängen. Die IP-Adressen wurden nach VLAN-Struktur vergeben. Nur Geräte im selben VLAN können miteinander kommunizieren.


### 📎 Anhang:
Im Anhang befinden sich Screenshots zu diesem Projekt
