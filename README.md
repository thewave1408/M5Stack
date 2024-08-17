# M5Stack
YAML and config for M5Stack devices


Make sure the following lines are part of the main YAML file in ESPHome:

```yaml
packages:
  # Uncomment the appropriate package for your project
  #PoESP32-enviv: github://thewave1408/M5Stack/PoESP32-enviv.yaml@main
  #PoESP32-btproxy-enviv: github://thewave1408/M5Stack/PoESP32-btproxy-enviv.yaml@main
  #atomlite-enviv: github://thewave1408/M5Stack/atomlite-enviv.yaml@main

esphome:
  name: ${name}
  friendly_name: ${friendly_name}
  name_add_mac_suffix: false

ota:
  - platform: esphome

api:
  encryption:
    key: changeme

```
