## Nintendo Wii Guide

!!! Info

    If you run into any issues during the course of this guide, refer to the [Issues](issues.md) section.


### Downloads

* [nfs2iso2nfs](https://github.com/NicoAICP/UWUVCI-Tools/raw/master/nfs2iso2nfs.exe)

* [DumpsterU](https://github.com/GaryOderNichts/DumpsterU/releases/latest/) (download the version for your OS)

#### Steps

**1.** Insert the USB drive into your Computer. Do not format the drive if promted to.

**2.** Open up DumpsterU on your PC. Ubuntu users may have to open it through the terminal.

**3.** Select your USB drive, insert your ``otp.bin`` and ``seeprom.bin`` into DumpsterU and click ``Ok``.

**4.** Select the Game you want to extract and select a place to store it. (You have to do this step with every game you want to extract.)

**5.** Copy the ``nfs2iso2nfs.exe`` file to the ``content`` folder of the dump.

**6.** Open Terminal/Command Prompt and run the commands for your respective operating system.

Windows:
```
cd [path to nfs2iso2nfs folder] 
nfs2iso2nfs.exe -dec
```

Ubuntu:
```
cd [path to nfs2iso2nfs folder]
wine nfs2iso2nfs.exe -dec
```

!!! success
    Congratulations, you now have your Nintendo Wii ROM!

!!! Info 

    If you want to see who contributed to this guide, go to the [Credits page.](credits.md)
