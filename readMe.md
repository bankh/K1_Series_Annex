### Table of Contents
I- Download and Install the Image 1.3.2 
IIa- [Fluidd installation and uninstallation (UI Option)](#fluidd-installation-and-uninstallation-ui-option)  
IIb- [Mainsail installation and uninstallation (UI Option)](#mainsail-installation-and-uninstallation-ui-option)  
III- [Pinout](#pinout)  
IV- [Root guide](#root-guide)  
V- [Additional References](#additional-references)  

❗__Warning:__❗ Moonraker running for a long time on the K1 series poses a risk of memory overflow!

### K1_Series_Annex
#### I- Download and Install the Image 1.3.2  

  The download link is [here](https://drive.google.com/file/d/1_wLlbcfyCP2RPORpwKGLmsMj5SPtc_uC/view?usp=drive_link).

#### IIa- Fluidd installation and uninstallation (UI Option)
  
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
  5) Into Fluidd, IP with 4408 port (e.g., 192.168.1.1:4408) should result in the following screenshot.

     ![image](https://github.com/bankh/K1_Series_Annex/assets/9688867/2583ea1f-3ed0-4de2-9e2f-28efc6731768)

#### IIb- Mainsail installation and uninstallation (UI Option)
   1) Put the same level directory file ( mainsail ) in the root directory of the U disk  

   2) Copy the files ( mainsail.sh and mainsail.tar ) to the directory ( /usr/data )
      
    
    $ cp /tmp/udisk/sda1/mainsail/* /usr/data/
    
      
   4) Install mainsail, moonraker, and nginx `$ /usr/data/mainsail.sh install`

   5) Uninstall mainsail, moonraker, and nginx `$ /usr/data/mainsail.sh unstall`

   6) Access to Mainsail: {IP}:4409 (e.g., 192.168.1.1:4409)

#### III- Pinout

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
  

#### IV- Root guide
The link for the manual is [here](https://github.com/bankh/K1_Series_Annex/blob/main/root%20guide/K1%20Series%20root%20guide.pdf).

Firmware-recovery-tool: https://github.com/CrealityOfficial/K1_Series_Annex/releases/tag/V1.0.0  
Release： https://github.com/CrealityOfficial/K1_Series_Klipper/releases/tag/V1.3.2.1  

#### V- Additional References:
- [Fluidd Documentation](https://docs.fluidd.xyz/)
- [Mainsail Documentation](https://docs.mainsail.xyz/)
- [Creality K1 K1 Max root access Use Prusa slicer, Klipper, Fluidd, Moonraker like a normal 3D printer](https://www.youtube.com/watch?v=l2JCWSBQczg)
