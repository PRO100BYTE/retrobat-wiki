---
description: Atari
---

# Atari ST

<div align="left">

<figure><picture><source srcset="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/91d85c7849cc550b0cac4e75cb8e0923d3b61b5e/art/logos/atarist-w.svg" media="(prefers-color-scheme: dark)"><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/52ff37c9e265587d006945a2ba695b5a962b3a3d/art/logos/atarist.svg" alt=""></picture><figcaption></figcaption></figure>

</div>

Computer - Lifespan: 1985 - 1993

{% embed url="https://en.wikipedia.org/wiki/Atari_ST" %}

## Information

<table data-header-hidden><thead><tr><th width="184"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>libretro: hatari</li><li>libretro: hatarib</li><li>hatari</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> atarist</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.st .msa .stx .dim .ipf .m3u .gemdos .zip .7z</td><td></td></tr></tbody></table>

## System Features

<table><thead><tr><th width="245">Retroachievements</th><th width="200">Netplay</th><th>Controller autoconfig</th></tr></thead><tbody><tr><td>lr-hatari: NO<br>lr-hatarib: NO<br>Hatari: NO</td><td>lr-hatari: NO<br>lr-hatarib: NO<br>Hatari: NO</td><td>lr-hatari: NO<br>lr-hatarib: NO<br>Hatari: NO</td></tr></tbody></table>

## BIOS

<table><thead><tr><th width="155">BIOS file</th><th width="207.03610108303252">Folder</th><th>md5 hash / remark</th></tr></thead><tbody><tr><td>tos.img</td><td><code>\bios</code></td><td>b2a8570de2e850c5acf81cb80512d9f6</td></tr><tr><td>emutos.img</td><td><code>\bios\hatari\tos</code><br><code>\bios\hatarib</code></td><td></td></tr><tr><td>tos102.img</td><td><code>\bios\hatari\tos</code><br><code>\bios\hatarib</code></td><td></td></tr><tr><td>tos106.img</td><td><code>\bios\hatari\tos</code><br><code>\bios\hatarib</code></td><td></td></tr><tr><td>tos104.img</td><td><code>\bios\hatari\tos</code><br><code>\bios\hatarib</code></td><td></td></tr><tr><td>tos206.img</td><td><code>\bios\hatari\tos</code><br><code>\bios\hatarib</code></td><td></td></tr></tbody></table>

## Controls

Use Pad2Key for this system if you need specific mapping, see the [Pad2Key ](../../../../../en/controllers/pad2key.md)section of this Wiki.

Here is the default mapping.

<table><thead><tr><th width="263">Retrobat Button</th><th>Atari ST key (libretro)</th></tr></thead><tbody><tr><td>START</td><td>Show/Hide virtual keyboard</td></tr><tr><td>SELECT</td><td>Toggle Mouse/Joy mode</td></tr><tr><td>D-PAD</td><td></td></tr><tr><td>Left analog stick</td><td>Directions (up, dow, left, right)</td></tr><tr><td>Right analog stick</td><td></td></tr><tr><td><img src="../../../../../en/.gitbook/assets/image (45).png" alt=""></td><td></td></tr><tr><td><img src="../../../../../en/.gitbook/assets/image (27).png" alt=""></td><td>Mouse button B</td></tr><tr><td><img src="../../../../../en/.gitbook/assets/image (13).png" alt=""></td><td>Fire/Mouse button A / press key in virtual keyboard</td></tr><tr><td><img src="../../../../../en/.gitbook/assets/image (47).png" alt=""></td><td>lr-hatari GUI</td></tr><tr><td>L1</td><td>Toggle Num Joy</td></tr><tr><td>R1</td><td>Change Mouse speed 1 to 6 (for gui and emu)</td></tr><tr><td>L2</td><td>Show/Hide status</td></tr><tr><td>R2</td><td>Sound on/off</td></tr><tr><td>L3</td><td></td></tr><tr><td>R3</td><td></td></tr></tbody></table>

### **Hatari**

<table><thead><tr><th width="263">Retrobat Button</th><th>Hatari</th></tr></thead><tbody><tr><td>SELECT</td><td>Open emulator menu</td></tr><tr><td>D-PAD</td><td>Joystick - D-pad</td></tr><tr><td><img src="../../../../../en/.gitbook/assets/image (27).png" alt=""></td><td>Joystick - FIRE</td></tr><tr><td>F11</td><td>Toggle fullscreen</td></tr><tr><td>F12</td><td>Emulator Menu</td></tr><tr><td>ALTGr + Q</td><td>Quit emulator</td></tr></tbody></table>

## Specific system information

### Mounting a "gemdos" hard drive image

Libretro Hatari-B core can automatically mount a "gemdos" hdd image within the emulated system.

In order to do this, the hdd to mount must be stored in the roms folder :

<div align="left">

<figure><img src="https://i.imgur.com/RscLeZw.png" alt=""><figcaption></figcaption></figure>

</div>

Next, create an empty text file in the same folder, name it with the exact same name as the folder and save it with the .GEM extension:

<div align="left">

<figure><img src="https://i.imgur.com/VAu6Ce9.png" alt=""><figcaption></figcaption></figure>

</div>

Additionnaly, it is possible to make lr-hatarib automatically run one of the program stored on the mounted gemdos HDD image.

To do so, create an empty text file in the roms\atarist folder that is named with the exact same name as the gemdos folder.

In the file, specify the following information:

```
#EXTM3U
#AUTO:<name of the program to autorun>
<name of the GEM file>
```

<div align="left">

<figure><img src="https://i.imgur.com/SvXLkHs.png" alt=""><figcaption></figcaption></figure>

</div>

Finally: save the text file with the ".m3u" extension and place it in the same folder as the image folder and the GEM file:

<div align="left">

<figure><img src="https://i.imgur.com/03PB7np.png" alt=""><figcaption></figcaption></figure>

</div>

In this example, RetroBat automatically:

* Launches hatarib and mounts the "The New Zealand Story" image in the emulated device
* Runs the program RUNME.TOS from the mounted drive (program is located in `C:\AUTO`)

{% hint style="warning" %}
Running .gemdos folders requires the TOS version 2.06 or emuTOS.
{% endhint %}
