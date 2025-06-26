# Gezielte Zugriffskontrolle mit VLANs & ACLs

In diesem Projekt wurde eine selective Zugriffssteuerung zwischen VLANs implementiert, um den Server in VLAN 5 (192.168.5.0/24) vor unerlaubten Zugriffen zu schützen. Nur die Geräte aus dem Büro-VLAN (192.168.2.0/24) sollten auf diesen Server zugreifen dürfen.


## Fazit
Durch diese Konfiguration wurde eine klare Zugriffsbeschränkung erreicht:

- Sicherheit: Unbefugte Zugriffe aus anderen VLANs werden unterbunden.

- Kontrolle: Nur autorisierte Nutzer (Büro-VLAN) können auf den Server zugreifen.

- Skalierbarkeit: Das Konzept lässt sich auf weitere VLANs und Dienste erweitern.
## 📎 Anhang:
Screenshots zur Topologie und Konfiguration befinden sich im Anhang
