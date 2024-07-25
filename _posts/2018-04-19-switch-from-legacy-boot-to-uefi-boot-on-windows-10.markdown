---
layout: post
title: "Switch from legacy boot to uefi boot on Windows 10"
---

# Why switch?
UEFI bring GPT witch remove some limitation of the legacy boot system:
- It permit to have a lot of partition on the same drive.
- You can have partition bigger than 2 Terabytes.

# prerequisite
prepare an windows install media and a UBS stick.
We will need it latter to run commands when windows will not be bootable anymore.
Go to the windows website and burn it to the key.

# legacy table partition to gpt
install AOMEI partition assistant and transform your hard drive into GPT (no data lost).
now your pc can’t boot anymore so we will work to change that.

# boot to the windows media key
and access to the console by clicking repair

# create a UEFI partition
for that use diskpart with the following constraints:
- partition of 500 MB in Fat32 in the first 2 Tera Bytes

# install windows boot loader in the UEFI partition
give letter to volume eufi and windows volume with diskpart
and run the folowing command:
``` powershell
bcdboot C:\windows /s G: /f UEFI
```
with C: the windows volume and G: the eufi volume

# done!
