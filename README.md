# docker-planefence-homeassistant
Home Assistant code for Planefence

The code in configuration.yaml will process MQTT messages from a dafault planefence installation and create a seonsor tracking the latest messages, and sensors for each attribute.
The sensors are slightly different for planefence and plane-alert.

The code in planealert.yaml configures an alert to your mobile phone via the Home Assistant app when an aircraft of interest is heard by your ADS-B station feeding Planefence, including an image.

The code in card.yaml will display the latest aircraft of interest on your dashboard, using the vertical stack in card.
