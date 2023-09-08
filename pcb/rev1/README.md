# Nyx (Rev 1)
An 65% layout hotswap PCB, with compatible many UDB position. Designed in KiCAD 6.99.

## Renders (KiCAD):
![top](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266492982-2acd0b19-bd5b-4b04-a34b-0fa794f08e4a.png)

![bottom](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266493147-460ce755-f65c-41db-b23a-45ed28d2b325.png)

## IRL images:
![top](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266494126-e4521b33-8b34-467d-9132-ffedfb2afbe9.png)

![bottom](https://github-production-user-asset-6210df.s3.amazonaws.com/24840279/266494269-aac8ded5-8b50-47da-8c89-4384b68b9a05.png)

## Features
- Uses the RP2040 MCU, with W25Q16BVSSIG (2 MB of external flash).
- Uses Kailh MX hotswap sockets.
- Added anti-shearing to the hotswap sockets.
- Holes of hotswap socket holes are plated, you can still solder in a switch, should a hotswap socket ever shear off for whatever reason.
- 65% layout (see below).
- Support 2 UDB positions.
- Support RGB Matrix, with SN74LVC1G17DBVR level shifter and SK6812Mini-E LED per-keys.
- Has cutout for gummy o-ring mount (Bakeneko65, ...).
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
