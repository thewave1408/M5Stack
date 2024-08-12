# M5Stack
YAML and config for M5Stack devices


Make sure the following lines are part of the main YAML file in ESPHome:

```yaml
packages:
  # Uncomment the appropriate package for your project
  #PoESP32-enviv: github://thewave1408/M5Stack/PoESP32-enviv.yaml@main
  #atomlite-enviv: github://thewave1408/M5Stack/atomlite-enviv.yaml@main

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
