# Projekt 12: DHCP im lokalen Netzwerk (Single-Segment-Netz)       

## Ziel des Projekts
Das Ziel dieses Projekts ist es, ein kleines Netzwerk mit einem Router als DHCP-Server zu erstellen, der automatisch IP-Adressen an Clients (PCs) vergibt. Damit lernst du die Funktionsweise des Dynamic Host Configuration Protocol (DHCP) kennen und kannst überprüfen, ob alle Geräte automatisch konfiguriert und miteinander verbunden sind.


## 🖥️  Geräte

Router	1:	Gateway und DHCP-Server              
Switch	1	                      
PCs	3


## 🌐 Netzwerkstruktur
Alle Geräte befinden sich im gleichen Netzwerksegment (ohne VLANs).
Der Router hat die feste IP-Adresse 192.168.1.1 und ist direkt mit einem Switch verbunden.
Die PCs hängen ebenfalls am Switch.

## ⚙️ DHCP-Konfiguration am Router

siehe im 📎 Anhang !

#### Erklärung:
- ip dhcp pool LAN: Erstellt einen DHCP-Pool mit dem Namen "LAN"

- network: Gibt den zu verteilenden Adressbereich an

- default-router: Gateway für die Clients

- excluded-address: Reserviert IPs 192.168.1.1–192.168.1.100 (z. B. für Drucker, Server oder manuelle Geräte)


## 📎 Anhang
Screenshots zur Topologie und Konfiguration befinden sich im Anhang                                           












## Für was braucht man DHCP?
Ohne DHCP müsste jeder Computer, jedes Smartphone, jeder Drucker und jedes andere netzwerkfähige Gerät, das sich mit einem Netzwerk verbindet, manuell mit einer eindeutigen IP-Adresse, Subnetzmaske, Standard-Gateway und DNS-Server-Informationen konfiguriert werden. Das wäre in größeren Netzwerken extrem aufwendig, fehleranfällig und unpraktisch.





