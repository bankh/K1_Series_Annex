### K1_Series_Annex

1. Fluidd installation and uninstallation
  
  >a) Put the same level directory file ( fluidd ) in the root directory of the U disk
  
  >b) Copy the files ( fluidd.sh and fluidd.tar ) to directory ( /usr/data ) `cp /tmp/udisk/sda1/fluidd/* /usr/data/`

  >c) Install Fluidd, moonraker and nginx `/usr/data/fluidd.sh install`
  
  >d) Unstall Fluidd, moonraker and nginx `/usr/data/fluidd.sh unstall`
  
  >e) Access to Fluidd
  >> {IP}:4408 (e.g., 192.168.1.1:4408)
  
  ❗__Warning:__❗ Moonraker running for a long time on the K1 series poses a risk of memory overflow!

2. Mainsail installation and uninstallation
   >a) Put the same level directory file ( mainsail ) in the root directory of the U disk  

   >b) Copy the files ( mainsail.sh and mainsail.tar ) to directory ( /usr/data )  `cp /tmp/udisk/sda1/mainsail/* /usr/data/`

   >c)Install mainsail, moonraker and nginx `/usr/data/mainsail.sh install`

   >d) Uninstall mainsail, moonraker and nginx `/usr/data/mainsail.sh unstall`

   >e> Access to Mainsail  
   >> {IP}:4409 (e.g., 192.168.1.1:4409)

3. Pinout

4. Root guide

Firmware-recovery-tool: https://github.com/CrealityOfficial/K1_Series_Annex/releases/tag/V1.0.0  
Release： https://github.com/CrealityOfficial/K1_Series_Klipper/releases/tag/V1.3.2.1  

**Additional References:**  
- [Fluidd Documentation](https://docs.fluidd.xyz/)
- [Mainsail Documentation](https://docs.mainsail.xyz/)
- [Creality K1 K1 Max root access Use Prusa slicer, Klipper, Fluidd, Moonraker like a normal 3D printer](https://www.youtube.com/watch?v=l2JCWSBQczg)
