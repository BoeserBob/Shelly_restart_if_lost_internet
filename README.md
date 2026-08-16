# Watchdog-Script: VPN Restart with Shelly plug if lost connection.

Dieser Script läuft auf dem Watchdog-Shelly-Plug eines fernen per VPN angebundenen Natzes.
An dem Shelly Plug hängen die FritzBox und der LTE-Stick für die Datenverbindung. 

Wenn die VPN Verbindung länger als 180Minuten verloren geht schaltet der Script die Shelly Plug aus.

WICHTIG: 
Auf der Shelly Plug muss unbedingt eingerichtet werden: 
- dass sie sich nach einigen Sekunden wieder selbst einschaltet 
- und der Ausgang eingeschaltet wird, wenn der Shelly mit Strom versorgt wird (um einen Wiederanlauf nach Stromausfall sicher zu stellen).


