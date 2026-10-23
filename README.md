# JettersCol-Eng

English fan translation of **Bomber Man Jetters - Game Collection** (GBA, Japan, `BOMJ`).

I found 2 ingame debug menus of sorts which are not documented anywhere on the internet that i can find.
ROM ADDRESS - 08024EA0 (file offset 0x24EA0)
U32 original value 08006489 / U16 original value 6489
to activate Battle Scene List change to 08005EB9 then enter Battle Mode
to activate the developers root debug menu change to 0802FE15 then enter Battle Mode.

I have found and replicated opening this menu on official hardware, mGBA, and Nintendo Switch Online NSO injection.

It seems a lot of its options were either scrubbed or unfinished so a lot of it will just leave you on a black screen or crash your game.

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
