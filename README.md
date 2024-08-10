# M5Stack
YAML and config for M5Stack devices


Make sure the following lines are part of the main YAML file in ESPHome:

```yaml
packages:
  PoESP320-enviv: github://thewave1408/M5Stack/main/PoESP32-enviv.yaml

esphome:
  name: ${name}
  name_add_mac_suffix: false
  friendly_name: ${friendly_name}

api:
  encryption:
    key: changeme

wifi:
  ssid: !secret wifi_ssid
  password: !secret wifi_password

```
