# Projekt 24: Drei Büros mit VLANs (inkl. WLAN)

## Projektziel
Ziel dieses Projekts war es, drei verschiedene Büros logisch zu trennen, indem jedem Büro ein eigenes VLAN zugewiesen wurde – inklusive eines drahtlosen Netzwerks für das „WLAN-Büro“. Es handelt sich um eine vereinfachte Unternehmensstruktur, die zeigt, wie VLANs eingesetzt werden, um Ordnung und Sicherheit ins Netzwerk zu bringen.

## 🧱 Netzwerkaufbau
Das Netzwerk besteht aus einem zentralen Switch, an dem alle Geräte angeschlossen sind. Die VLANs trennen die drei Büros voneinander:

| Büro          | VLAN   | Geräte                 | IP-Bereich     |
| ------------- | ------ | ---------------------- | -------------- |
| Büro 1        | VLAN 2 | PC2, PC3               | 192.168.2.0/24 |
| Büro 2        | VLAN 3 | Server1                | 192.168.3.0/24 |
| Büro 3 (WLAN) | VLAN 4 | Access Point + Laptop3 | 192.168.4.0/24 |


Der Router verbindet das gesamte interne Netzwerk mit dem „Internet“ (oder einer anderen übergeordneten Verbindung) über die Verbindung 210.210.0.0/30.

## 📶 Besonderheit: WLAN-Büro
- Ein Access Point ist in VLAN 4 angeschlossen

- Laptop3 verbindet sich kabellos über diesen AP

- Auch WLAN-Clients erhalten IPs aus dem VLAN-4-Netz und bleiben getrennt von anderen VLANs

### 📎 Anhang
Screenshots zur Topologie und Konfiguration des Access Points befinden sich im Anhang
