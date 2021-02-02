# arduino-sketches

## Arduino

## Installation
```
snap install arduino
```
## Configuration

### Ajouter la board
* voir dans https://developer.sensirion.com/tutorials/create-your-own-co2-monitor/
* ajouter
  https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
dans Fichier > Préférences > Url de Gestionnaire de cartes supplémentaires
* Relancer arduino

### Installer les croquis

* git clone du projet et copier les fichiers dans ~/Arduino (attention, si
  install avec snap il faut installer dans ~/snap/arduino/50/Arduino/

### Conecter l'arduino
* brancher l'arduino
* Outils > ports
* Récupération des informations de la carte
* Outils > typres de carte > ESP32 Dev Module

### Commpilation
* choisir le croquis
* si dépendance à une bibliothèque, retrouver la dépendance dans le
  Outils > Gérer les bibliothèques
* Vérifier (1er bouton de gauche)
* Téléverser (2eme bouton)

