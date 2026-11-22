Deux services pour la domotique Thread et Matter, en réseau hôte :

- **OTBR** (OpenThread Border Router) : routeur de bordure Thread, avec une clé USB RCP (par exemple Sonoff Zigbee 3.0 Dongle Plus V2 flashée en RCP).
- **Matter Server** (python-matter-server) : serveur Matter à connecter à Home Assistant.

À l'installation, renseigne le chemin de la clé dans `/dev/serial/by-id/` et l'interface réseau de l'hôte (`ip a`).
