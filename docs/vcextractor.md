## wiiu-vc-extractor Guide

### Downloads

* [wiiu-vc-extractor](https://github.com/wheatevo/wiiu-vc-extractor/releases/tag/latest/) (download the respective .zip file for your operating system)

#### Steps

**1.** Extract the contents of ``wiiu-vc-extractor-xxxxx-x64.zip`` to a folder on your computer.

**2.** Insert your USB storage device or SD card into your Wii U.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - If prompted, **do not** format any USB devices through the Wii U.

**3.** Launch the internet browser on your console and open `dumplingapp.com`.

**4.** Tap "Launch dumpling". <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- If your console freezes for more than 10 seconds, hold down the Power button for 4 seconds and reboot.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Once rebooted, [reset the browser's save data](https://en-americas-support.nintendo.com/app/answers/detail/a_id/1507/~/how-to-delete-the-internet-browser-history) and try again.

**5.** Select "Dump Digital Games".

**6.** Select all the games you want to dump using the DPad/A button and then press Start.

**7.** Make sure the target destination is set to ``SD card`` and the account is set accordingly, then select Start to begin dumping. (this could take a while)

**8.** Once finished, press start to exit Dumpling and insert your SD card into your computer.

**9.** Go into dumpling/games/[name of the game you dumped]/ on your SD card.  
● If your game is a NES/SNES/GBA/FDS game, go into ``/code`` and copy the .rpx file into the same folder that you extracted wiiu-vc-extractor into.

● If your game is a GBA game, go into ``/content`` and copy the .psb.m file and the .bin file into the same folder that you extracted wiiu-vc-extractor into.

● If your game is a PCE/TurboGrafx-16 game, go into ``/content`` and copy the .pkg file into the same folder that you extracted wiiu-vc-extractor into.

**10.** Open Terminal/Command Prompt and run the following commands:

``cd [path to your wiiu-vc-extractor folder]``

**Linux and macOS only:** ``chmod +x wiiuvcextractor``

``wiiuvcextractor [dump file without the brackets]``

!!! success
    Congratulations, you now have your ROM! You can find the file in your wiiu-vc-extractor folder.

!!! Info
    If you want to see who contributed to this guide, go to the [Credits page.](credits.md)
