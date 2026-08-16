# Watchdog-Script: VPN Restart with Shelly plug if lost connection.

Dieser Script läuft auf dem Watchdog-Shelly-Plug eines fernen, per VPN an mein Heimnetz angebundenen Netzes.
An dem Shelly Plug hängen die FritzBox und der LTE-Stick für die Datenverbindung. 
Wenn die VPN Verbindung länger als 180 Minuten verloren geht schaltet der Script die Shelly Plug aus.

WICHTIG: Auf der Shelly Plug muss unbedingt eingerichtet werden: 
- Um den Router nach dem Reset wieder zu starten: Shelly Plug muss den Strom nach einigen Sekunden wieder selbst einschalten 
- Um einen Wiederanlauf nach Stromausfall sicher zu stellen: Shelly Plug Eingangs-/ Ausgangseinstellungen auf "Konfiguriere das Shelly Gerät so, dass es angeht, wenn es mit Strom versorgt wird" einstellen.

... sonst heist es hinfahren und von Hand wieder einschalten :-)


