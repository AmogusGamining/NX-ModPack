# NX-ModPack


A mod pack to easily and seamlessly mod your switch.<br>
<br>
This is a simple and bare bone mod pack with no bloatware whats so ever. I will try to keep this up to date as any of its contents get updated.<br>
<br>
Keep in mind it is always best to follow the [Switch Modding Guide](https://switch.hacks.guide/) and do everything yourself.


 - [Contents](#CONTENTS)
 - [Installation](#INSTALLATION)
 - [Homebrew](#INSTALLINGHOMEBREW)
 - [Disclaimer](#DISCLAIMER)
 - [Credits](#CREDITS)


## CONTENTS

 - [Hekate-Nyx](https://github.com/CTCaer/hekate)
 - [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
 - [Sys-Patches](https://github.com/impeeza/sys-patch)
 - exosphere.ini
 - DNS-MITM
 - Homebrew:
   * [Goldleaf](https://github.com/xortroll/goldleaf)
   * [NX-HBmenu](https://github.com/switchbrew/nx-hbmenu)
   * Daybreak, Haze, Reboot to Payload (preinstalled with atmosphere)

## INSTALLATION
<details>

 - [NX-ModPack](#1-install-nx-modpack)
 - [SD CARD](#2-sd-card)
 - [Tegra RCM](#3-tegra-rcm)
 - [Boot into Hekate](#4-booting-into-hekate)
 - [Hekate Settings](#5-hekate-settings)
   * [Part 1](#part-1)
   * [Part 2](#part-2)
 - [Emummc Setup](#6-EmuMMCEmuNand-Setup)
 - [Launch]()
 
### 1. Install NX-ModPack
 Install the latest release of the ModPack from [here](https://github.com/AmogusGamining/NX-ModPack/releases/tag/NX-ModPack).
 <br>


 
### 2. SD CARD
 Open SD Card on PC and format it (backup Nintendo Folder if you have one) <br>
 Now in the empty SD Card move the **contents** of "DRAG BEFORE" folder inside.<br>
 <br>
 It should look like this <br>
 <img width="685" height="306" alt="image" src="https://github.com/user-attachments/assets/e4f6bbc7-65b6-4110-82c5-47806bd04b49" /> <br>
 After this unplug your SD card from the PC, shutdown your switch and put it in your switchs SD slot<br>
 <br>


### 3. Tegra RCM
 Run the Tegra RCM Installer setup in the zip folder.<br>
 <img width="656" height="318" alt="image" src="https://github.com/user-attachments/assets/9de4b95c-8460-4f7e-a7a7-ae0a622303fb" /> <br>
 <br>
 once installed, open Tegra RCM and go to settings tab and click install Driver<br>
 <img width="388" height="321" alt="image" src="https://github.com/user-attachments/assets/866a1955-1e0d-4945-9091-56ae94bc5757" /><br>
 <br>
 After that, go to payload tab and load the Hekate Payload in the zip<br>
 <img width="1077" height="532" alt="image" src="https://github.com/user-attachments/assets/9d5b3faf-c65b-49cd-a03c-ca0da7196632" />
 <br>


### 4. Booting into Hekate
 Put an RCM Jig on the right Joycon Rail and Load into RCM Mode by holding volume up button and pressing power button <br>
 (Note: The screen will stay off in RCM Mode, if it boots by doing this then the RCM Jig didnt make good enought contact with the pins on joycon rail) <br>
 Once in RCM Mode, connect your Switch to your PC using a USB <br>
 Tegra RCM Payload menu should say RCM OK, Select Inject payload.<br>
 <img width="386" height="320" alt="Screenshot 2026-06-23 153921" src="https://github.com/user-attachments/assets/e72826a9-3e27-4471-9774-1827981ff9e6" /> <br>
 Now you will be booting into Hekate Nyx<br>
 <br>


 ### 5. HEKATE SETTINGS 
 #### Part-1
  In Hekate first go to tools and select "Partition SD Card" <br>
  <img width="1280" height="720" alt="Partition 1" src="https://github.com/user-attachments/assets/8e982b7b-dc8c-4725-b532-a6c931689e79" /> <br>
  <br>
  Move the Emummc(RAW) slider to 29Full <br>
  <img width="1280" height="720" alt="Partition 2" src="https://github.com/user-attachments/assets/ab50c3b9-750d-4c0f-9621-9eb6f3f5a774" /><br>
  And select next step to partition.<br>
  <br>

  
 #### Part-2
  Now, in tools tab go to USB Tools<br>
  <img width="1280" height="720" alt="USB Tools" src="https://github.com/user-attachments/assets/7f185ced-2376-44ab-84de-9378dc299f54" /><br>
  <br>
  And select sd card<br>
  <img width="1280" height="720" alt="USB Tools2" src="https://github.com/user-attachments/assets/a7892ebf-07c8-449a-ad2d-1cdc80d1e21f" /><br>
  <br>
  Connect ur switch to PC using a USB Cable and move the contents of DRAG AFTER folder into sd card root<br>
  your SD cards root should look like this <br>
  <img width="698" height="401" alt="image" src="https://github.com/user-attachments/assets/3abfb6e9-4933-4bf1-80ac-8e34b631d8a2" /><br>
  **Do not delete any new files that are not in picture**<br>
  <br>


### 6. EmuMMC/EmuNand Setup
  Go to home menu and select Emummc<br>
  <img width="1280" height="720" alt="Emummc" src="https://github.com/user-attachments/assets/3c372483-ee6b-44b9-a1f8-b75dcee2c3fe" /><br>
  <br>
  select create emummc<br>
  <img width="1280" height="720" alt="Emummc 2" src="https://github.com/user-attachments/assets/ea73ba2c-83d4-4d2b-953f-a0a33f712473" /><br>
  <br>
  SD Partition, and then part 1<br>
  <img width="1280" height="720" alt="Emummc 3" src="https://github.com/user-attachments/assets/b9143f21-5931-491b-8aae-fe4c53fd6b78" /><br>
  <br>
  This will take some time so wait.


</details>


## INSTALLING HOMEBREW

 Move the .nro file into the switch folder in your SD card <br>
 <br>
 <img width="675" height="366" alt="Screenshot 2026-06-23 133155" src="https://github.com/user-attachments/assets/2959d374-a8ab-4ede-b1ef-e84a71758d79" /> <br>
 
 - Some homebrew require extra files, in that case, move the contents of zip folder of homebrew into root of SD card<br>
 <br>
 
## DISCLAIMER

I am **NOT**, in any way, responsible for any damage (or ban) done to your switch if you use this Modpack.<br>

## CREDITS

 - [CTCaer](https://github.com/CTCaer) for the creation of [Hekate-Nyx](https://github.com/CTCaer/hekate)
 - [Atmosphere-NX](https://github.com/Atmosphere-NX) for the creation of [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
 - [Impeeza](https://github.com/impeeza) for the creation of [Sys-Patches](https://github.com/impeeza/sys-patch)
 - [XorTroll](https://github.com/XorTroll) for the creation of [Goldleaf](https://github.com/xortroll/goldleaf)
 - [Switchbrew](https://github.com/switchbrew) for the creation of [NX-HBmenu](https://github.com/switchbrew/nx-hbmenu)
 - [Switch Modding Guide](https://switch.hacks.guide/) for an in depth explaination of modding your switch
