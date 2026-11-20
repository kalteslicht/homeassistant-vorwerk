# Repository Archived

**Notice:** The original repository is now archived and will no longer be maintained.  

This fork is primarily meant for my own personal use to keep this integration functioning for my VR200. I do not plan to do any development above that.
Currently the integrations works with Home Assistant 2026.10
If this is helpfull to you, please feel free to download and use.

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

## homeassistant-vorwerk

Home assistant integration to control Vorwerk VR vacuum cleaners.

With the new Vorwerk App and authentication the Home Assistant Neato component dropped the vorwerk support. This integration is based on the neato component with the new Vorwerk authentication flow.

## Supported vacuum cleaners

- VR200
- VR300 (without map sensors)

## Installation

### HACS

1. In HACS, add `https://github.com/kalteslicht/homeassistant-vorwerk` as a custom repository of type **Integration**.
2. Download the integration and restart Home Assistant.

### Manual

The integration files sit at the top level of this repository. Copy `__init__.py`, `config_flow.py`, `const.py`, `manifest.json`, `sensor.py`, `services.yaml`, `strings.json`, `switch.py`, `vacuum.py` and the `translations/` folder into `<HA config directory>/custom_components/vorwerk/`, then restart Home Assistant.
