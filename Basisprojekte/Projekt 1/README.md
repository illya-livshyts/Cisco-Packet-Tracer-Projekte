## Projekt 1: Punkt-zu-Punkt-Verbindung (2 PCs direkt)

Zwei PCs über ein Crossover-Kabel direkt miteinander verbinden und die Kommunikation über IP-Adressen testen.


🖥️ Geräte: -2 PCs ,- 1 Crossover-Kabel

## Schritte:
1.Geräte platzieren:  
In Cisco Packet Tracer zwei PCs aus der Geräteliste ziehen.

2.Verkabelung:  
Verwende ein Crossover-Kabel, um PC0 und PC1 direkt zu verbinden.

3.IP-Adressen zuweisen:  
PC0
IP: 192.168.1.1

Subnetzmaske: 255.255.255.0

PC1
IP: 192.168.1.2

Subnetzmaske: 255.255.255.0  

4.Verbindung testen:   
Öffne die Eingabeaufforderung auf PC0

Eingabe: ping 192.168.1.2

Die Antwortpakete zeigen, dass die Verbindung funktioniert.





## 🧠 Erklärung:
In diesem Projekt habe ich zwei PCs direkt mit einem Crossover-Kabel verbunden. Jeder PC bekam eine IP-Adresse im gleichen Subnetz. Dadurch können sie direkt kommunizieren. Mit dem ping-Befehl konnte ich prüfen, ob die Verbindung funktioniert. Das Projekt zeigt, wie einfache Punkt-zu-Punkt-Netzwerke aufgebaut werden.
