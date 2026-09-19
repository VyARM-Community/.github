# VyARM Community

**Bringing VyOS to ARM-based single-board computers.**

VyARM Community is an independent open-source project focused on porting and adapting VyOS to ARM64 single-board computers. Our goal is to make VyOS routing, firewall and VPN functionality available on compact, energy-efficient hardware, with ready-to-use images and clear installation instructions.

The images include additional network, Wi-Fi and cellular modem drivers and firmware for supported hardware. Actual peripheral support depends on the board, available drivers and firmware, and hardware testing.

## Board images and documentation

Each board has its own repository with installation instructions, setup helpers, update guidance and image releases.

| Board | Images and documentation |
| --- | --- |
| Radxa ROCK 5B | [rock-5b](https://github.com/VyARM-Community/rock-5b) |
| Radxa E52C | [radxa-e52c](https://github.com/VyARM-Community/radxa-e52c) |

**The list of supported boards will grow gradually.** New boards are added as integration work and hardware testing progress. Check each board's README and release notes for available downloads, validation status and known limitations. A listed board does not imply that every peripheral or hardware function is supported.

## Shared development

Board support is developed through a shared ARM64 builder, allowing common improvements to be reused across devices while keeping board-specific requirements explicit.

Source code and development: [VyOS ARM64 board builder](https://github.com/frogro/vyos-arm64-board-builder).

Hardware test results, reproducible bug reports and contributions are welcome. Please use the relevant board repository for board-specific issues.

## Community project

These are unofficial community images. VyARM Community is not affiliated with or endorsed by the VyOS project or the hardware manufacturers. Upstream software and trademarks remain the property of their respective owners, and component licenses continue to apply.

## Support the project

Contributions help cover hardware, testing, maintenance and development time.

[Support via PayPal](https://paypal.me/FGrootens)
