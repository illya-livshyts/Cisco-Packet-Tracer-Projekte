# Netzwerksicherheit – Schutz vor kompromittiertem Router 

## 📝 Ausgangssituation
Im Netzwerk wurde Router1 gehackt. Es bestand die Gefahr, dass der Angreifer Zugriff auf interne VLANs (Abteilungen) erlangt
## Ziel
Den Zugriff von Router1 (bzw. aus dem Internet) auf die internen VLANs blockieren, um das interne Netzwerk zu schützen und eine Ausbreitung des Angriffs zu verhindern.
## 📝 Erklärung:
Wir haben auf Router0 eine Access Control List (ACL) eingerichtet.

Diese ACL blockiert den Zugriff von außen (aus dem Internet) auf bestimmte interne VLANs. Dadurch wird verhindert, dass der kompromittierte Router1 interne IP-Adressen erreichen oder ausspionieren kann.

Die Regel wurde auf dem Eingang des Interfaces von Router0 aktiviert, welches mit dem Internet verbunden ist. So schützen wir unser Netzwerk vor weiteren Angriffen aus dem Internet.



### 📎 Anhang:
Screenshots zur Topologie und Konfiguration befinden sich im Anhang                  
-Und die letzten drei Fotos zeigen eine verkürzte Variante, wie man es auch machen könnte.-
