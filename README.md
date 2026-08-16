# Shelly_restart_if_lost_internet

Dieser Script läuft auf dem Watchdog-Shelly-Plug eines fernen per VPN angebundenen Natzes.
An dem Shelly Plug hängen die FritzBox und der LTE-Stick für die Datenverbindung. 

Wenn die VPN Verbindung länger als 180Minuten verloren geht schaltet der Script die Shelly Plug aus.
Auf der Shelly Plug muss unbedingt eingerichtet werden, dass sie sich nach einigen Sekunden wieder selbst einschaltet und der Strom eingeschaltet wird.


