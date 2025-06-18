#  Projekt 16: Dynamisches Routing mit OSPF (Open Shortest Path First)            

## Projektziel
In diesem Projekt wurde OSPF (ein dynamisches Routing-Protokoll) konfiguriert, um eine automatische Wegfindung zwischen mehreren Routern in einem drei-Router-Netzwerk zu ermöglichen. Dadurch konnten alle Endgeräte (PCs) netzwerkübergreifend miteinander kommunizieren, ohne statische Routen manuell eintragen zu müssen.

## 🔁 Was wurde gemacht?
- Auf allen Routern wurde OSPF aktiviert
- Alle Netzwerkbereiche wurden mit dem OSPF-Prozess bekannt gemacht
- Die /30-Subnetze dienen als Punkt-zu-Punkt-Verbindungen zwischen den Routern
- OSPF findet automatisch die besten Pfade für alle Routen und hält sie aktuell

## Ergebnis
- Jeder PC kann mit jedem anderen kommunizieren, obwohl sie sich in unterschiedlichen Netzwerken befinden.
- Die Router lernen automatisch die Wege über das OSPF-Protokoll.
- Das Netzwerk ist skalierbar – bei Änderungen (z. B. neue Router) passt sich die Routing-Tabelle dynamisch an.

## 📌 Warum OSPF?
OSPF ist ein Link-State-Protokoll, das schnell konvergiert und effizient mit großen Netzwerken umgehen kann.

Es eignet sich perfekt für strukturierte, mittelgroße Netzwerke mit mehreren Pfaden zwischen den Routern.

