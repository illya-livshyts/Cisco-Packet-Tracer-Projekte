# Projekt 17: Dynamisches Routing mit OSPF + VLANs + Loopbacks
In Projekt 17 geht es darum, ein größeres Unternehmensnetzwerk mit mehreren Standorten zu simulieren, in dem dynamisches Routing mit OSPF verwendet wird. Jeder Standort besitzt eigene VLANs für Benutzergruppen, und alle Router sind über OSPF im Backbone-Bereich (Area 0) miteinander verbunden.

Zusätzlich ist ein Router (Router3) mit dem „Internet“ verbunden, sodass das gesamte Netzwerk darüber ins Internet gelangen kann. Jeder Router hat eine Loopback-Adresse, die ebenfalls ins OSPF-Routing eingebunden ist, z. B. für Netzwerkmanagement.

Das Ziel ist, zu zeigen, wie man VLANs, dynamisches Routing und Internetzugang in einem professionellen Netzwerkdesign kombiniert. 


## Geräte

- 3 Router: Router2 (Zentrale), Router4 (Standort A), Router5 (Standort B)

- 1 Router: Router3 (Internet-Gateway)

- 2 Switches: Switch0 (Standort A), Switch1 (Standort B)

- 1 Server: Internet-Server (Server0)

- 4 PCs: PC0 bis PC3 (mit VLAN-Zugehörigkeit)

- Loopbacks: Je 1 Loopback pro Router für OSPF-Routing


## 📎 Anhang
Screenshots zur Topologie und Konfiguration befinden sich im Anhang
