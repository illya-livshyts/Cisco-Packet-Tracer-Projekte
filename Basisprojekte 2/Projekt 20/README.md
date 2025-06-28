# Projekt 20: VPN-Verbindung zwischen Filiale und Zentralem Office

## 📌 Ziel des Projekts
In diesem Projekt wurde eine VPN-Verbindung (Virtual Private Network) eingerichtet, um zwei Standorte sicher miteinander zu verbinden:

- Filiale (192.168.1.0/24)

- Zentrales Office (192.168.2.0/24)

Die beiden Netzwerke liegen geografisch getrennt und kommunizieren über das Internet. Um die Daten vor fremdem Zugriff zu schützen, wurde ein VPN-Tunnel zwischen den beiden Routern aufgebaut. Dadurch wirken beide Standorte wie ein gemeinsames lokales Netzwerk – verschlüsselt und geschützt.

### 🔧 Technische Umsetzung
- Jeder Standort hat ein eigenes Subnetz (192.168.1.0/24 und 192.168.2.0/24).

- Die Verbindung zwischen den Standorten läuft über das Netzwerk 210.210.1.0/30 und 210.210.2.0/30.






## 📎 Anhang
Screenshots zur Topologie und Konfiguration befinden sich im Anhang


### 🔐 Was ist VPN und warum ist es wichtig?
VPN (Virtual Private Network) ist eine Technologie, die ein sicheres und verschlüsseltes Netzwerk über das Internet aufbaut.
Man nutzt VPN, um private Netzwerke über öffentliche Verbindungen zu verbinden – also z. B. eine Filiale mit einem Hauptbüro, wie in diesem Projekt.

## Vorteile von VPN:  


- Sicherheit: Daten werden verschlüsselt übertragen.

- Datenschutz: Keine Einsicht durch Dritte im Internet.

- Remote-Zugriff: Geräte an entfernten Standorten können sicher auf zentrale Ressourcen zugreifen.

- Kostenersparnis: Kein teures Mietleitungsnetz nötig.
