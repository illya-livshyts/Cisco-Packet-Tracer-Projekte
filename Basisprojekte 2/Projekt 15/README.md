# Projekt 15 – Statisches NAT für gezielte Serverkommunikation

## Ziel des Projekts
- Das Ziel war, wie in Projekt 14, Geräte aus privaten Netzwerken (VLAN 2 und VLAN 3) mit einem externen Server (213.234.20.2) kommunizieren zu lassen – über NAT auf Router0.
- Der entscheidende Unterschied: In Projekt 15 wurde ein statisches NAT speziell zwischen dem internen Server (Server0, 192.168.3.2) und dem externen Server (Server1, 213.234.20.2) eingerichtet.


## 🔄 Unterschied zu Projekt 14
| Projekt        | NAT-Typ                              | Zweck                                                                                                   |
| -------------- | ------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| Projekt 14     | Dynamisches NAT (Overload)           | Mehrere Geräte teilen sich 1 öffentliche IP                                                             |
| **Projekt 15** | **Statisches NAT + dynamisches NAT** | Benutzer surfen wie gewohnt, aber der Server ist direkt erreichbar (z. B. für Webdienste, E-Mail, etc.) |



## 💡 Warum statisches NAT?
Ermöglicht dauerhaften Zugriff auf einen internen Dienst (z. B. Webserver) von außen.

Wird verwendet, wenn bestimmte öffentliche IP-Adressen fest einem Dienst zugeordnet werden sollen.

Realistische Simulation z. B. für Webhosting in Firmen oder Rechenzentren.


## 📎 Anhang

Screenshots zur Topologie und Konfiguration befinden sich im Anhang
