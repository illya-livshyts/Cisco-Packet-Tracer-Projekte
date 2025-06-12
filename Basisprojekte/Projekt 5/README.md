# Projekt 5: Drei Switches verbunden über einen Multilayer-Switch
In diesem Projekt werden drei Access-Switches mit einem zentralen Multilayer-Switch verbunden. Ziel ist es, die drei Switches miteinander zu verbinden, sodass Kommunikation zwischen allen Geräten möglich ist – über den zentralen Switch.

### Ziele   
-Drei Switches über einen Multilayer-Switch verbinden

-Verbindung testen

-Netzwerkstruktur verstehen

## 🖥️Geräte
3x Switches  
1x Multilayer-Switch    
6x Kupferkabel (Straight-Through)


## 🖧 Netzwerkaufbau   
Verbindungsschema:
Switch0 ↔ Multilayer-Switch0 (2 Kabel)

Switch1 ↔ Multilayer-Switch0 (2 Kabel)

Switch2 ↔ Multilayer-Switch0 (2 Kabel)

      

###  🧪 Test
Da keine PCs beteiligt sind, wurde nur die physikalische Verbindung getestet. Alle Verbindungen waren aktiv.

## Hinweis:
Was macht das Spanning Tree Protocol (STP)?              
-STP verhindert Schleifen, indem es einen Hauptpfad aktiv lässt und den zweiten blockiert – bis er gebraucht wird.       

-Wenn du zwei Switches mit zwei Kabeln verbindest, entsteht eine Redundanz (doppelte Verbindung).         
Das ist gut, weil:            
✅ Ausfallsicherheit: Wenn ein Kabel defekt ist, funktioniert das Netzwerk trotzdem.        
✅ Lastverteilung: Der Traffic kann sich auf beide Kabel aufteilen (wenn EtherChannel verwendet wird).


### 📎 Anhang:
Im Anhang befinden sich Screenshots zu diesem Projekt   
