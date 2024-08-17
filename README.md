# M5Stack
YAML and config for M5Stack devices


Make sure the following lines are part of the main YAML file in ESPHome:

```yaml
packages:
  # Uncomment the appropriate package for your project
  #thewave1408.PoESP32-enviv: github://thewave1408/M5Stack/PoESP32-enviv.yaml@main
  #thewave1408.PoESP32-btproxy-enviv: github://thewave1408/M5Stack/PoESP32-btproxy-enviv.yaml@main
  #thewave1408.atomlite-enviv: github://thewave1408/M5Stack/atomlite-enviv.yaml@main

esphome:
  name: ${name}
  friendly_name: ${friendly_name}
  name_add_mac_suffix: false

api:
  encryption:
    key: changeme

ota:
  - platform: esphome

```
