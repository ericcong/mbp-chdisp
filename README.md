# mbp-chdisp
Display switcher for Macbook Pro.

Tested on Debian 9.1 + Macbook Pro 8,1.

## Installation

Download `mbp-chdisp.deb`, then run: `sudo dpkg -i mbp-chdisp.deb`.

## Usage

- `mbp-chdisp`: if external display (DP) is connected, then open both external and internal displays, otherwise open internal display only.
- `mbp-chdisp e`: open external display only.
- `mbp-chdisp i`: open internal display only.
- `mbp-chdisp m`: open both displays, but in mirror mode.

## Udev

This package also includes a udev rule: when external display connects or disconnects, then run `mbp-chdisp` once.