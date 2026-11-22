Deux services pour la domotique Thread et Matter, en réseau hôte :

- **OTBR** (OpenThread Border Router) : routeur de bordure Thread, avec une clé USB RCP (par exemple Sonoff Zigbee 3.0 Dongle Plus V2 flashée en RCP).
- **Matter Server** (matter.js, successeur de python-matter-server) : serveur Matter à connecter à Home Assistant via `ws://<ip>:5580/ws`. Tableau de bord sur `http://<ip>:5580/`.

À l'installation, renseigne le nom de la clé tel qu'il apparaît dans `/dev/serial/by-id/` (sans le chemin) et l'interface réseau de l'hôte (`ip a`).
