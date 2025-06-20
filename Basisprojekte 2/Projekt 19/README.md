# Projekt 19: Access Control List (ACL)

Eine Access Control List (ACL), zu Deutsch Zugriffssteuerungsliste, ist ein grundlegender Sicherheitsmechanismus in der IT, der den Zugriff auf Ressourcen in Computersystemen und Netzwerken regelt. Man kann sie sich wie eine Liste von Regeln vorstellen, die festlegen, wer (oder was) auf welche Ressource zugreifen darf und welche Aktionen dabei erlaubt sind

Netzwerke (Router, Switches, Firewalls): Dies ist der häufigste Kontext, in dem man von ACLs spricht. Hier werden sie eingesetzt, um den Netzwerkverkehr zu filtern. Eine Netzwerk-ACL kann beispielsweise festlegen:

- Welche IP-Adressen (Quell- und/oder Ziel-IP) Datenpakete senden oder empfangen dürfen.
- Welche Protokolle (z. B. TCP, UDP, ICMP) erlaubt sind.
- Welche Portnummern (z. B. Port 80 für HTTP, Port 443 für HTTPS) für bestimmte Dienste genutzt werden dürfen.
- Ob der Datenverkehr eingehend (in das Netzwerk) oder ausgehend (aus dem Netzwerk) ist. Netzwerk-ACLs dienen dazu, die Netzwerksicherheit zu erhöhen, indem sie unerwünschten Datenverkehr blockieren, bestimmte Dienste einschränken oder sogar Denial-of-Service-Angriffe (DoS) abwehren.

#### Unterschied zwischen Standard ACLs und Extended ACLs:

#### Standard ACLs:
Sie kann den gesamten Verkehr von oder zu einer bestimmten Quell-IP-Adresse (oder einem Subnetz) erlauben oder blockieren.

📎siehe  anlage (image_2/3)
#### Extended ACL (Erweiterte Zugriffssteuerungsliste):
Sie ermöglichen eine sehr feingranulare Kontrolle über den Netzwerkverkehr.
- Quell-IP-Adresse
- Ziel-IP-Adresse
- Protokoll (z. B. TCP, UDP, ICMP, IP)
- Quell-Port (z. B. welcher Dienst sendet das Paket)
- Ziel-Port (z. B. welcher Dienst soll das Paket empfangen, z. B. Port 80 für HTTP, Port 443 für HTTPS, Port 23 für Telnet)
📎siehe anlage (image_4)

