# Nyx (Rev 2)
An 65% multi-layout soldering PCB, with compatible many UDB position. Designed in KiCAD 6.99.

## Renders (KiCAD):
![top](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266519279-bc3a87d4-214c-4e03-a59d-91766fe48b5a.png)

![bottom](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266519610-2c079056-77ac-422e-afd6-8a8347304aa6.png)

## IRL images:
**Coming soon!**

## Features
- Uses the RP2040 MCU, with ZD25Q80BNIGR (1 MB of external flash).
- Use soldering switches.
- 65% multi-layout (see below).
- Support 5 UDB positions.
- Support RGB Indicator, with SN74LVC1G17DBVR level shifter and SK6812Mini-E LED per-keys.
- Support RGB Underglow, using RGB WS2812 strip and soldering on PCB.
- Has cutout for gummy o-ring mount (Bakeneko65, ...) and other mount.
- Physical BOOT button for getting into bootloader if [bootmagic](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_bootmagic.md) isn't available. Acessible under PCB.
- SWD header for debugging.
- ESD chip (SRV05-4) to prevent damage from electrostatic discharge.
- Polyfuse to prevent overcurrent.
- Optimized for manufacturing and assembly with JLCPCB.
- Bonus: Curved traces and teardrops.

## Firmware
**Coming soon!**

## Layout
![layout](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266519774-4b6f8642-ef79-410e-a580-7e641b4cd07f.png)
