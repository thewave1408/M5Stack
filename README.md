# M5Stack
YAML and config for M5Stack devices


Make sure the following lines are part of the main YAML file in ESPHome:

---
packages:
  ApolloAutomation.MSR-1: github://ApolloAutomation/MSR-1/Integrations/ESPHome/MSR-1.yaml
esphome:
  name: ${name}
  name_add_mac_suffix: false
  friendly_name: ${friendly_name}
api:
  encryption:
    key: qJdcUxYf2juP8+vd/U/J2TDy54zbDX6DQ007xb1aCnU=


wifi:
  ssid: !secret wifi_ssid
  password: !secret wifi_password
---
