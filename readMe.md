### Table of Contents
1- [Fluidd installation and uninstallation (UI Option)](#fluidd-installation-and-uninstallation-ui-option)  
2- [Mainsail installation and uninstallation (UI Option)](#mainsail-installation-and-uninstallation-ui-option)  
3- [Pinout](#pinout)  
4- [Root guide](#root-guide)  
[Additional References](#additional-references)  

❗__Warning:__❗ Moonraker running for a long time on the K1 series poses a risk of memory overflow!

### K1_Series_Annex
#### Fluidd installation and uninstallation (UI Option)
  
  1) Put the same level directory file ( Fluidd ) in the root directory of the USB disk
  2) Copy the files ( fluidd.sh and fluidd.tar ) to the directory ( /usr/data )
  ```
  $ cp /tmp/udisk/sda1/fluidd/* /usr/data/
  ```
  3) Install Fluidd, moonraker and nginx
  ```
  $ ./fluidd.sh install
  ```
  4) To uninstall `fluidd`, `moonraker` and `nginx`  
  ```
  ./fluidd.sh unstall
  ```
  5) Into Fluidd, IP with 4408 port (e.g., 192.168.1.1:4408)
  
#### Mainsail installation and uninstallation (UI Option)
   1) Put the same level directory file ( mainsail ) in the root directory of the U disk  

   2) Copy the files ( mainsail.sh and mainsail.tar ) to the directory ( /usr/data )  `cp /tmp/udisk/sda1/mainsail/* /usr/data/`
      
   3) Install mainsail, moonraker and nginx `/usr/data/mainsail.sh install`

   4) Uninstall mainsail, moonraker and nginx `/usr/data/mainsail.sh unstall`

   5) Access to Mainsail: {IP}:4409 (e.g., 192.168.1.1:4409)

#### Pinout

 <table>
    <tr>
        <td><img src="./pin out/Nozzle-board-A-en.JPEG" alt="Dummy Image"></td>
    </tr>
    <tr>
        <td><img src="./pin out/Nozzle-board-B-en.JPEG" alt="Dummy Image"></td>
    </tr>
    <tr>
        <td><img src="./pin out/motherboard-en.PNG" alt="Dummy Image"></td>
    </tr>
    <tr>
        <td><img src="./pin out/motherboard-pinout.JPEG"></td>
    </tr>
</table>
  

#### Root guide
The link for the manual is [here](https://github.com/bankh/K1_Series_Annex/blob/main/root%20guide/K1%20Series%20root%20guide.pdf).

Firmware-recovery-tool: https://github.com/CrealityOfficial/K1_Series_Annex/releases/tag/V1.0.0  
Release： https://github.com/CrealityOfficial/K1_Series_Klipper/releases/tag/V1.3.2.1  

#### Additional References:
- [Fluidd Documentation](https://docs.fluidd.xyz/)
- [Mainsail Documentation](https://docs.mainsail.xyz/)
- [Creality K1 K1 Max root access Use Prusa slicer, Klipper, Fluidd, Moonraker like a normal 3D printer](https://www.youtube.com/watch?v=l2JCWSBQczg)
