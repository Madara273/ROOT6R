# ROOT6R
Warning! during the rooting process, all data from your device will be erased, so make a backup copy of important data for you!
Disclaimer: I am not responsible for your damaged devices, so do it at your own risk. The instruction works if your hands grow from the right place and you have previously worked with adb fastboot and edl mode.

#Instructions:
Download the unlock tool from the link https://unlocktool.net/download/.
Run the unlock tool program.
The next step will be to transfer the RedMagic 6R device to EDL mode.
For this, we need to install adb fastboot on the PC and the QUALCOMM HS-USB QDLoader 9008 driver.
Next, connect the device and enter the command -- adb reboot edl --.
In the unlock tool window of the connected ports, you will see COM (port number) QUALCOMM HS-USB QDLoader 9008.
Select the UFS type in the firehose option, navigate to the directory where the firehoseRM6R.elf file is located, select it, and click READ GPT.
Next, you will see general information about the device and the partitions that can be flashed
Locate LUN4 and select boot_b, right click and select option "write (boot_b.img) find the patched boot.img in explorer and click "load"
Do the same with vbmeta_b in LUN4, but with a correspondingly patched vbmeta.img
That's it, your redmagic 6r device is rooted, press "reboot" in the unlock tool and wait for your phone to boot.

The root will depend on the choice of kernel: if you choose kitsune_patched.img then download Kitsune Magisk.
If apatch_patched.img then download Apatch

1. Kernels patched by Kitsune Mask and Apatch are in the boot folder, so you can flash them as you wish.

2. The firehoseRM6R.elf programmer is located in the firehose folder.

3. The patched vbmeta is in the vbmeta folder.

4. QUALCOMM HS-USB QDLoader 9008 driver located in the program+driver folder

Add-ons:
#source code - nx666j kernel
#unlock tool
#platform-tools
#UnlockTool-2024-04-14-0.exe
#Qualcomm-HS-USB-QDLoader-9008-Driver

Support -- m10173488@gmail.com
