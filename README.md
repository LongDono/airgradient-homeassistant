# airgradient_esphome
ESPHome definition for an AirGradient DIY device to send data to HomeAssistant and AirGradient servers while maintaining a similar functionality and look to the official AirGradient Arduino IDE sketch

## Configuration
If all sensors (PMS5003, Senseair S8, SHT3x) are connected, airgradient.yml should be fully ready
If some sensors are not installed, comment or remove the associated sections in sensor: and display: and http_request.post:

To add your wifi SSID and password, either remove the "!secret" section and type in your information, or edit the secrets.yaml file with
your information so it is not hard coded into the device's file.

## Fonts
You may substitute any font as desired.  Included font "Liberation Sans" is open source and very similar to Arial that is
used by the official AirGradient Arduino sketch
