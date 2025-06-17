# Projekt 14: NAT zwischen privaten VLANs und externem Server

## Ziel des Projekts               
In diesem Projekt soll getestet werden, wie Geräte aus privaten Netzwerken (VLAN 2 und VLAN 3) über Router0 mit einem externen Server (213.234.20.2) kommunizieren können.
Dazu wurde auf Router0 NAT (Network Address Translation) eingerichtet. Ziel ist es:

- den Internetzugriff von VLAN 2 und VLAN 3 über eine öffentliche IP zu ermöglichen.

- den privaten Server und die Benutzergeräte in einem internen Netz zu halten.   

- die Verbindung zum öffentlichen Server (Server1) über NAT abzusichern und realitätsnah zu simulieren. 


## 🌐 Struktur und Funktion
VLAN 2: Benutzergeräte mit privaten IP-Adressen.

VLAN 3: Interner Server, z. B. für Datei- oder Webdienste.

Router0 hat NAT eingerichtet: Es übersetzt interne IPs (192.168.x.x) in die öffentliche IP 213.234.10.1.

Der Datenverkehr wird über Router1 zum externen Server (213.234.20.2) weitergeleitet.

Das Netzwerk simuliert den realen Zugriff von Firmen-PCs auf das Internet mit einer einzigen öffentlichen IP.

## 📎 Anhang
Screenshots zur Topologie und Konfiguration befinden sich im Anhang



## Warum NAT?
- Private IPs sind nicht im Internet routbar.

- NAT ermöglicht es mehreren Geräten, mit einer einzigen öffentlichen IP online zu gehen.

- Dies ist Standard in Heim- und Firmennetzwerken – auch aus Sicherheits- und Adressknappheitsgründen.


NAT steht für Network Address Translation (Netzwerkadressübersetzung). Es ist eine Technologie, die in Computernetzwerken verwendet wird, um die IP-Adressen von Datenpaketen beim Übergang zwischen verschiedenen Netzwerken zu ändern. Der Hauptzweck von NAT ist es, private IP-Adressen in einem lokalen Netzwerk in eine oder mehrere öffentliche IP-Adressen umzuschreiben, um die Kommunikation mit dem Internet zu ermöglichen.
