--Warning--
don't use this if you are a newbie, I am not responsible for your broken devices. This app is dangerous for small users which can cause your device to crash completely, in that case only unbrick tool and jtag programmer will help you.
--------------------------------------------
1_step -- install [ Unofficial Qualcomm Firehose / Sahara / Streaming / Diag Tools :) ]
--note -- just copy this text -- (Unofficial Qualcomm Firehose / Sahara / Streaming / Diag Tools :)) -- and paste into the search engine - go to github developer and install the program depending on your OS.
----------------------------------------------------- -
2_step -- connect the device to your computer or other phone in edl mode and run the command --lsusb-- you see something in the device image ******* 9008. If you see it, go to step 3.
----------------------------------------------------- -
3_step -- execute a series of commands:

edl w boot_b kitsune_patched.img --loader=firehoseRM6R.elf --memory=ufs --lun=4

edl w vbmeta_b patch-vbmeta.img --loader=firehoseRM6R.elf --memory=ufs --lun=4
----------------------------------------------------- -
Step 4 -- Unplug the device from usb and restart your device by holding the power button until you hear a vibration.
----------------------------------------------------- -
that's all your device is rooted.

-- note -- all files must be in one folder for ease of entering commands, if you change the location of files from the archive, then specify the path to each file accordingly!

Support -- m10173488@gmail.com
