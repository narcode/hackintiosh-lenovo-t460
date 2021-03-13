# hackintosh-lenovo-t460

EFI and goodies for hackintosh Lenovo T460 with Clover 


## my specs:
- Lenovo T460 running Mojave 10.14.6
- Processor 2.5 IntelCore i5 (KabyLake)
- 24 GB RAM (this laptop can go up to 32)
- Samsung SSD 
- Intel HD Graphics 520
- Changed wifi card to Broadcom compatible card (BCM4360 14e4:43a0)

## what works:
almost everyhting, don't have any issues really. Sometimes after OS updates I need to rollback IOPCIFamily kext for the wifi to work again.

# note:
There is no config.plist in the repo so not suitable to just clone and expect it to work. Refer to the guide at the bottom or ask me for the config file. Better to read, try and learn than just cloning anc copy pasting.

I also have an elitebook HP 830 G5 with OpenCore to test both bootloaders. However I am really happy with how this one is working so decided to keep the Lenovo the way it is. 

# Credits
Most of the ppl workikng on hackintoshes along the years. Like Rehabman and others from the different forums. All the needed knowledge is there just from reading. I saved a lot of time thanks to tlucks repo: https://github.com/tluck/Lenovo-T460-Clover and his guide at http://www.insanelymac.com/forum/topic/315451-guide-lenovo-t460-macos-with-clover/
