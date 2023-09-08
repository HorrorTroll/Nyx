# Nyx (Rev 2)
An 65% layout hotswap PCB, with compatible many UDB position. Designed in KiCAD 6.99.

## Renders (KiCAD):
![top](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266495495-ada12fac-4504-4193-94e4-05d94097ccdb.png)

![bottom](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266496340-ec65f72b-89ab-40c6-af25-8d523b10abb3.png)

## IRL images:
![top](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266497428-95830504-bd11-4372-b6dc-fb0da79f468a.png)

![bottom](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266497708-23783d42-6310-4af3-b9fc-13338b00b72d.png)

## Features
- Uses the RP2040 MCU, with ZD25Q80BNIGR (1 MB of external flash).
- Uses Kailh MX hotswap sockets.
- Added anti-shearing to the hotswap sockets.
- Holes of hotswap socket holes are plated, you can still solder in a switch, should a hotswap socket ever shear off for whatever reason.
- 65% layout (see below).
- Support 5 UDB positions.
- Support RGB Matrix, with 2 IS31FL3729 LED drivers and MHT151RGBCT LED per-keys.
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
![layout](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266491147-ab977b04-3b1e-4dfe-ad79-53e195404652.png)
