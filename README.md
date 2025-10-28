# MQTT-installation-raspberry-pi (en cours de développement)
Installation et configuration de MQTT sur raspberry pi
## Mise à jour
`sudo apt update && sudp apt upgrade`
## Installer
`sudo apt install -y mosquitto mosquitto-clients`
## Configuration du fichier .conf
`sudo nano /etc/mosquitto/mosquitto.conf`<br>

  Ajouter les lignes dans le fichier:<br>
  
`listener 1883` Ecoute sur le port 1883<br>
`allow_anonymous true` Autorise la connexion sans identifiant et sans mot de passe
