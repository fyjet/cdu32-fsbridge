# Introduction fsbridge
Pont FSUIPC/MQTT en python 3.8 pour tourner sur l'ordinateur exécutant Flight Simulator (Verison 2002 à FSX).

Le depot cdu32 https://github.com/fyjet/cdu32 sert d'afficheur distant

# Installation
## Installation des prerequis (win 7 à win11)
### FS et FSUIPC
Installer Flight Simulator et FSUIPC
FS2002 et FS9: FSUIPC3.999
FSX: FSUIPC4

### Python
Installer python 3.8.10 32bits
Télécharger FSUIPCSDK v4 (présent dans le répertoire bin) et éxecuter l'installer FSUIPCSDK pour python 3.8 (a partir de FSUIPC SDK v4)
pip install paho-mqtt

### Mosquitto
Installer mosquitto 1.4.9 (voir répertoire bin) et les librairies complémentaires

### Tortoise GIT 
Installer TortoiseGit 1.7.2.0

## Installation fsbridge
Faire un clone git du depot fsbridge ou telecharger un release https://github.com/fyjet/fsbridge/tags

# Execution
Lancer Flight Simulator (FSX, FS9, FS2002)
Lancer mosquitto
Aller dans le répertoire fsbridge
Lancer fsbridge
`python fsbridge.py`
Brancher le device esp32cdu

# Configuration
fsbridge.ini
