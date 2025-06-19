# Projekt 18: Dynamisches Routing mit EIGRP 

In diesem Projekt wird ein kleines Netzwerk mit drei Routern dargestellt, die über dynamisches Routing mit EIGRP (Enhanced Interior Gateway Routing Protocol) verbunden sind. Jeder Router ist mit einem eigenen Subnetz und einem PC verbunden. Zusätzlich wurden Loopback-Interfaces verwendet, um zusätzliche Netzwerke zu simulieren.


## Ziel:

Alle Router sollen automatisch Routen zueinander lernen, damit die Endgeräte in den verschiedenen Netzwerken miteinander kommunizieren können – ohne manuelle statische Routen.

## Unterschied zwischen EIGRP und OSPF:

| Merkmal         | EIGRP                                 | OSPF                                |
| --------------- | ------------------------------------- | ----------------------------------- |
| Typ             | Cisco-proprietär (früher) / nun offen | Offen (Standardprotokoll)           |
| Routing-Metrik  | Bandbreite, Delay (kombiniert)        | Kosten basierend auf Bandbreite     |
| Geschwindigkeit | Sehr schnell                          | Etwas langsamer                     |
| Komplexität     | Einfach zu konfigurieren              | Etwas komplexer                     |
| Konvergenzzeit  | Sehr schnell                          | Gut, aber etwas langsamer als EIGRP |
| Einsatzgebiet   | Vor allem in Cisco-Netzwerken         | Universell in allen Netzwerken      |


## 📎 Anhang
Screenshots zur Topologie und Konfiguration befinden sich im Anhang


