# Z2M-MLI-404011-Blueprint

Home Assistant Blueprint for Müller-Licht Remote compatible with Zigbee2MQTT v2.x

## Important Note
Double check the bindings of your remote in Zigbee2MQTT,in column "Cluster" genLevelCtrl, genOnOff, lightingColorCtrl must be available. If not, enter settings:

 Under Devices > Remote, activate bindings
    (Source: Coordinator, Dest. Endpoint: 1, Cluster: genLevelCtrl, genOnOff, lightingColorCtrl).
    Press buttons on the remote while clicking "Bind" to keep it awake.

## Import of Blueprint into Homeassistant

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Firimitenkan%2FZ2M-MLI-404011-Blueprint%2Fblob%2Fmain%2FZ2M-MLI-404011-remote.yaml)
