# sp108e_ha

This integration is for the SP108E controller


### Pending testing

on / off, color and brightness are supported, mono color effects are good,
presets with colors work but ymmv with rgb wiring...

### Installation

Copy or clone into `<config_dir>/custom_components/sp108e_ws2815/`.

Restart the HA

Following the restart:

Add the following entry in your `configuration.yaml`:

```yaml
# led strip
light:
  - platform: sp108e_ws2815
    host: ip address, ie: 10.0.1.124
    name: 'your name here'
```
