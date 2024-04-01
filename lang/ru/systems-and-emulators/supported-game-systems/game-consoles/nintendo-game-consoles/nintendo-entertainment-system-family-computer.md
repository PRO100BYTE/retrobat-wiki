---
description: Nintendo
---

# Nintendo Entertainment System - Family Computer

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><img src="https://raw.githubusercontent.com/fabricecaruso/es-theme-carbon/master/art/logos/nes.svg" alt="" data-size="original"></td><td><img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Family_Computer_logo.svg" alt="" data-size="original"></td><td></td></tr></tbody></table>

Game Console - Lifespan: 1983 - 2003

{% embed url="https://en.wikipedia.org/wiki/Nintendo_Entertainment_System" %}

## Information

<table data-header-hidden><thead><tr><th width="184"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>Emulators</strong></td><td><ul><li>libretro: fceumm</li><li>libretro: nestopia</li><li>libretro: mesen</li><li>mednafen</li><li>mesen</li><li>ares</li><li>bizhawk: NesHawk</li><li>bizhawk: QuickNes</li></ul></td><td></td></tr><tr><td><strong>Games Location</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="1f4c1">📁</span> roms \ <span data-gb-custom-inline data-tag="emoji" data-code="1f4c2">📂</span> nes</td><td></td></tr><tr><td><strong>File extensions</strong></td><td>.fds .nes .wad .zip .7z</td><td></td></tr></tbody></table>

## Features

<table><thead><tr><th width="256">Retroachievements</th><th width="243">Netplay</th><th>Controller autoconfig</th></tr></thead><tbody><tr><td>lr-fceumm: YES<br>lr-nestopia: YES<br>lr-mesen: YES<br>Mednafen: NO<br>Mesen: NO<br>Ares: NO<br>BizHawk: YES</td><td>lr-fceumm: YES<br>lr-nestopia: YES<br>lr-mesen: YES<br>Mednafen: NO<br>Mesen: NO<br>Ares: NO<br>BizHawk: NO</td><td>lr-fceumm: YES<br>lr-nestopia: YES<br>lr-mesen: YES<br>Mednafen: YES<br>Mesen: YES<br>Ares: YES<br>BizHawk: YES</td></tr></tbody></table>

## BIOS

There is no BIOS files needed to run games.

## Controls

| RetroBat key                                                                             | NES key |
| ---------------------------------------------------------------------------------------- | ------- |
| START                                                                                    | START   |
| SELECT / BACK                                                                            | SELECT  |
| D-PAD                                                                                    | D-PAD   |
| Left analog stick                                                                        | D-PAD   |
| Right analog stick                                                                       |         |
| ![A](<../../../../../en/.gitbook/assets/image (27).png>)                                 | B       |
| ![B](<../../../../../en/.gitbook/assets/image (13).png>)                                 | A       |
| <img src="../../../../../en/.gitbook/assets/image (47).png" alt="" data-size="original"> | A       |
| <img src="../../../../../en/.gitbook/assets/image (45).png" alt="" data-size="line">     | B       |

<div align="left">

<figure><img src="https://i.imgur.com/ulQC9m2.png" alt=""><figcaption></figcaption></figure>

</div>

## Specific System Information

### Custom textures

The libretro:mesen core allows to load custom texture packs.

To do so you need to place the custom texture pack in the `\bios\HdPacks` folder in a dedicated directory that has the same name than the game file, for example if your game name is `Mega Man (USA).nes`, the texture pack folder must be named `Mega Man (USA)`

<div align="left">

<figure><img src="https://i.imgur.com/0t1gw0h.png" alt=""><figcaption></figcaption></figure>

</div>

{% hint style="info" %}
It is very important that the sha1 hash of your game file matches the sha1 located in the "hires.txt" file from the texture pack folder:
{% endhint %}

<div align="left">

<figure><img src="https://i.imgur.com/KAQVQlV.png" alt=""><figcaption></figcaption></figure>

</div>

<div align="left">

<figure><img src="https://i.imgur.com/b04EdoH.png" alt=""><figcaption></figcaption></figure>

</div>

Then, select the **Libretro: mesen** emulator for the game or the system:

<div align="left">

<figure><img src="https://i.imgur.com/QUAN6n2.png" alt=""><figcaption></figcaption></figure>

</div>

Next you need to enable the Custom Textures options in the Advanced Settings > Visual Rendering section of the Game Options or Advanced Systems Options:

<div align="left">

<figure><img src="https://i.imgur.com/Un77eUl.png" alt=""><figcaption></figcaption></figure>

</div>
