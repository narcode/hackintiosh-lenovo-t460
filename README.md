# hackintosh-lenovo-t460

EFI and goodies for hackintosh Lenovo T460 with OpenCore, tuned for macOs Ventura

Most of this update is based on https://www.tonymacx86.com/threads/success-thinkpad-t460-opencore-ventura.325050/. Great work there! This EFI just differs in the config.plist to accomodate the Broadcom wifi card. If not for that post I would have probably stayed in Catalina.

## my specs:
- Lenovo T460 running Mojave 10.14.6
- Processor 2.5 IntelCore i5 (KabyLake)
- 24 GB RAM (this laptop can go up to 32)
- Samsung SSD 
- Intel HD Graphics 520
- Changed wifi card to Broadcom compatible card (BCM4360 14e4:43a0)

## what works:
almost everyhting, don't have any issues really. With this new EFI even sleep is working fine, which was a bit broken in Catalina.

# note:
There is no config.plist in the repo so not suitable to just clone and expect it to work. Refer to the guide at the bottom or ask me for the config file. Better to read, try and learn than just cloning anc copy pasting.


# Credits
Most of the ppl workikng on hackintoshes along the years. Like Rehabman and others from the different forums. All the needed knowledge is there just from reading. Also thanks to the people behind OpenCode and Clover.

https://dortania.github.io/OpenCore-Install-Guide/

