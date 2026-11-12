# SYR Connect - Home Assistant Integration - FORK
# This is a fork of https://github.com/alexhass/conelclearpro_connect -- many Thanks to his effort on this project!
Please visit his project first!

Home Assistant installs the packages **automatically** when:

1. The integration is added through the UI.
2. Home Assistant is restarted after the installation.

For detailed system requirements and troubleshooting, see [REQUIREMENTS.md](REQUIREMENTS.md).

## Disclaimer

### IMPORTANT: Read this before using the integration

This integration controls water treatment and water shut-off systems. Improper configuration or malfunctioning automations could result in water damage, system failures, or property damage.

- **Use at your own risk**: This software is provided "as is" without warranty of any kind.
- **Test thoroughly**: Always test automations in safe conditions before deploying them.
- **Critical systems**: Valve control automations can shut off the entire water supply and must be tested carefully.
- **No liability**: The authors and contributors are not responsible for any damages, water damage, property damage, or other issues resulting from the use of this integration.
- **Cloud dependency**: This integration relies on the SYR Connect cloud service, whose availability is not guaranteed.
- **Backup plan**: An alternative access to the water shut-off valve must exist in case of system failure.

Installing and using this integration means acknowledging these risks and agreeing to use it responsibly.

## License

Apache License 2.0, see [LICENSE](LICENSE)

## Credits

- Inspired by [ioBroker.syrconnectapp](https://github.com/TA2k/ioBroker.syrconnectapp) adapter from TA2k.
- Many thanks to SYR IoT-Development-Team for sharing the logos.
- this is a fork of https://github.com/alexhass/conelclearpro_connect -- many Thanks to his effort on this project!


This is a modified fork of SYR Connect by Alexander Hass
(https://github.com/alexhass/syr_connect).
Modifications: renamed to conelclearpro_connect, changed branding/icons.