# Batgui

BatGui is a software provided with Retrobat and available at the root of your Retrobat folder

<div align="left">

<figure><img src="https://i.imgur.com/NRJN9Ju.png" alt=""><figcaption><p>BatGui.exe</p></figcaption></figure>

</div>

**The tool allows you to:**

* Manage [retrobat.ini](../../en/advanced-features/retrobat.ini.md) config file
* Manage System List
* Edit Gamelists (update game metadata)
* Generate .m3u file for [Xbox360 ](../../en/systems-and-emulators/supported-game-systems/game-consoles/microsoft-consoles/xbox-360.md#adding-xbla-xbox-live-arcade-games)and [PS3 ](../../en/systems-and-emulators/supported-game-systems/game-consoles/sony/playstation-3.md#adding-ps3-games)emulators
* Convert iso/cue format into CHD format
* Change the version of the SDL library and reset controller configuration

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h02_01.png" alt=""><figcaption></figcaption></figure>

</div>

### Retrobat ini

With BatGui.exe, you can edit the settings of your retrobat.ini file

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h06_55.png" alt=""><figcaption></figcaption></figure>

</div>

### System list

In this menu it is possible to update `es_systems.cfg` file, for example it is possible to remove an extension for a system.

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h09_57.png" alt=""><figcaption></figcaption></figure>

</div>

### Gamelist editor

In this menu it is possible to update `gamelist.xml` file for a system, metadata of individual games can be updated here as well as medias of games.

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h11_39.png" alt=""><figcaption></figcaption></figure>

</div>

### M3U Creator

In this menu it is possible to generate automatically the .m3u file in your [`\roms\ps3`](../../en/systems-and-emulators/supported-game-systems/game-consoles/sony/playstation-3.md#adding-ps3-games) or [`\roms\xbox360`](../../en/systems-and-emulators/supported-game-systems/game-consoles/microsoft-consoles/xbox-360.md#adding-xbla-xbox-live-arcade-games) folders for games installed in the emulator.

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h20_00.png" alt=""><figcaption></figcaption></figure>

</div>

### CHD Manager

In this menu it is possible to convert a ISO/CUE rom format into CHD format for emulators that support CHD format.

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h24_48.png" alt=""><figcaption></figcaption></figure>

</div>

### Change SDL library version and reset controller configuration

The "SDL Library Selector" menu allows you to reset controller configuration. This might be useful in case of conflict in the controller configuration module.\
Just click the "Reset GamePad config" button, all controller configuration will be deleted (except keyboard), and RetroBat will prompt you to configure your controller(s) again.\
Thie action performs a reinitialization of the **es\_input.cfg** file located in the `emulationstation\.emulationstation` folder of your RetroBat installation.

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h25_29.png" alt=""><figcaption></figcaption></figure>

</div>

From the "SDL Library Selector" menu, you will also be able to choose between different SDL versions. This option might be useful if some of your controllers are not correctly recognized as a last resort option (always start from the more recent, and try the versions from the most recent to the oldest).\
To do so, choose a DLL from the dropdown list, and click "Close". Then click "Reset GamePad config". You can now start RetroBat and reconfigure your controller.

<div align="left">

<figure><img src="../../en/.gitbook/assets/2024-02-18_08h26_14.png" alt=""><figcaption></figcaption></figure>

</div>
