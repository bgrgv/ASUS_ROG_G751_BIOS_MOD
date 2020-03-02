# G751 Unlocked BIOS

##### WARNING : FLASHING / ERASING CURRENT BIOS INVOLVES RISK. PROCEED UNDER YOUR OWN RISK

### This BIOS is an modded version of the stock image from the OEM. 

##### Features :
- Unlocked access to ICC Overclocking lib
- Per core control
- Complete manual control over
-- Manual parameter(s) config for non Optimus GPUs [ the /JL variant isn't supported yet ]
-- Tj Max Temp [!CAUTION]
-- Triple Point Temp [!CAUTION]
-- Boot time Performance / Battery mode
-- Acoustic control for SSDs and other devices [ depends on HW support ]
-- Override OS performance setting
-- Customised ThunderBolt security

#### Known issues : 
- Graphics settings aren't accessible on the JL variant, probably due to a physically disabled chipset.

###  Flashing : 
- Make sure to take a dump before you proceed.
- Use flasher from Asus : https://dlcdnets.asus.com/pub/ASUS/nb/Apps_for_Win10/Winflash/Winflash_Win10_64_VER301.zip
- Flash the provided image
### Bricked ?
- Place the backup image in the root of a USB Flash [ FAT32 only ] drive and connect to the first USB port on the left side [ID : 0] and invoke the failsafe mechanism by pressin CTRL + HOME keys at the same time.
