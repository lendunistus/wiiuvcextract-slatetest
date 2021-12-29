## wiiu-vc-extractor Guide

### Downloads

* [wiiu-vc-extractor](https://github.com/wheatevo/wiiu-vc-extractor/releases/tag/2.0.0/) (download the respective .zip file for your operating system)

* [Dumpling](https://github.com/emiyl/dumpling/releases/latest/) (download ``dumpling.zip``)

#### Steps

**1.** Insert your SD card into your computer.

**2.** Extract the contents of ``dumpling.zip`` to the root of your SD card.

**3.** Extract the contents of ``wiiu-vc-extractor-xxxxx-x64.zip`` to a folder on your computer.

**4.** Insert your SD card into your Wii U and power your Wii U on.

**5.** Launch The Homebrew Launcher using your preferred method.

**6.** Launch Dumpling.

**7.** Select "Dump Digital Games".

**8.** Select all the games you want to dump using the DPad/A button and then press Start.

**9.** Make sure the target destination is set to ``SD card`` and the account is set accordingly, then select Start to begin dumping. (this could take a while)

**10.** Once finished, press start to exit Dumpling and insert your SD card into your computer.

**11.** Go into dumpling/games/[name of the game you dumped]/ on your SD card.  
● If your game is a NES/SNES/GBA/FDS/TurboGrafx-16 game, go into ``/code`` and copy the .rpx file into the same folder that you extracted wiiu-vc-extractor into.

● If your game is a GBA game, go into ``/content`` and copy the .psb.m file and the .bin file into the same folder that you extracted wiiu-vc-extractor into.

● If your game is a PCE game, go into ``/content`` and copy the .pkg file into the same folder that you extracted wiiu-vc-extractor into.

**12.** Open Terminal/Command Prompt and run the following commands:

``cd [path to your wiiu-vc-extractor folder]``

**Linux and macOS only:** ``chmod +x wiiuvcextractor``

``wiiuvcextractor [dump file without the brackets]``

!!! success
    Congratulations, you now have your ROM! You can find the file in your wiiu-vc-extractor folder.

!!! Info
    If you want to see who contributed to this guide, go to the [Credits page.](credits.md)
