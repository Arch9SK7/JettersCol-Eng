# JettersCol-Eng

English fan translation of **Bomber Man Jetters - Game Collection** (GBA, Japan, `BOMJ`).


THIS IS A WIP AND A NEW HEADACHE TO WORK ON. Give time. I may or may not eventually finish this.

## Prerequisites
* **Python 3 + Pillow:** runs the dump and build tools. Install Pillow with `pip install pillow`.
* **A clean ROM:** an untouched `Bomber Man Jetters - Game Collection (Japan).gba`
  (SHA-1 `55a6ef08c00e5c02b256424495d9f90f6924cb7a`) in the project root. Any file name works,
  because the tools find it by its checksum.
* **Windows:** `tools\armips.exe` and `tools\flips.exe` are included for the build. On macOS/Linux, use
  `python tools/build.py --direct` (no armips needed unless you add ASM hacks).

## Credits
* Arch9SK7: translation, graphics and hacking
* armips (Kingcom), Floating IPS (Alcaro)
