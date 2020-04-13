## Dual Boot Guide
This tutorial guides you through the step-by-step procedure to dual boot **Ubuntu 18.04** with **Win 10**.

### Steps

 1. Take data backup.
 2. Download Ubuntu ISO file from [official website](https://ubuntu.com/download/desktop).
 3. Create a live ***bootable USB*** of that file using [Rufus](https://rufus.ie/). 
 [ Target System : BIOS or UEFI ]
 4. Disable [fast startup](https://help.uaudio.com/hc/en-us/articles/213195423-How-To-Disable-Fast-Startup-in-Windows-10) ( Quick Boot ) in Windows.
 5. Disable [secureboot](https://support.avira.com/hc/en-us/articles/360003038074-How-do-I-disable-UEFI-Secure-Boot-) in UEFI. [ F10 - BIOS Settings ]
 6. Boot the system using the bootable USB [ Esc - Boot Menu ] with ***legacy*** option.
 7. Manual Installation : Installation Type -> Something Else\
 Free Space (+)
    -	20 GB, ***Ext4, /***
    -	8 GB, ***Swap Area***
    -	< REST >, ***Ext4, /home***

> **Note :** To replace existing Ubuntu OS, just format the the / partition and enter the required credentials.

### References 

 - https://itsfoss.com/swap-size/
 - https://help.uaudio.com/hc/en-us/articles/213195423-How-To-Disable-Fast-Startup-in-Windows-10
 - https://support.avira.com/hc/en-us/articles/360003038074-How-do-I-disable-UEFI-Secure-Boot-
