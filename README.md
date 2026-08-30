# Z2M-MLI-404011-Blueprint

Home Assistant Blueprint for Müller-Licht Remote to compatible with Zigbee2MQTT v2.x

## Important Note
Double check the bindings of your remote in Zigbee2MQTT,in column "Cluster" genLevelCtrl, genOnOff, lightingColorCtrl must be available. If not, enter settings:

 Under Devices > Remote, activate bindings
    (Source: Coordinator, Dest. Endpoint: 1, Cluster: genLevelCtrl, genOnOff, lightingColorCtrl).
    Press buttons on the remote while clicking "Bind" to keep it awake.