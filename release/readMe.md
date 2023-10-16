The download link is [here]().

Guide
Scope of version update for version 1.3.2.1: 1.3.1.19-1.3.2.1.
Applicable Printer: K1 Max&K1

Upgrade Guide:
Click on the screen to upgrade, wait for the upgrade to complete, then Click on Settings - Self-Check - check Input Shaping and Bed Leveling, click Start Detection, and after calibration is complete, proceed with printing.

Root Guide:
Click on Settings - Root Account Information - Agree root Warning - View root account and password.
If you do not agree to the root agreement, you will not be able to use SSH to log in to the root account.

Root Risks:
please refer to the root warning displayed on the printer screen.
Enabling services like Moonraker may occasionally lead to excessive memory usage and system crashes.
Rooted devices can still enjoy hardware after-sales services within the warranty period, but root-related software technical support services will not be provided.
In case of firmware-related issues after rooting, support is available for rolling back to version V1.3.1.19."
### Known Issues:
Updating from version 1.3.0.x to the latest version results in a disconnection from the Creality Cloud., and you need to rebind with Creality Cloud.
Change List
Bug Fixes:
Fixed the problem of the privacy policy page not refreshing smoothly.
Fixed the issue of the print completion pop-up window still existing when printing from another terminal, causing an issue when clicking stop print during printing.
Fixed the password error pop-up issue that occurs after clicking forget network.
Fixed the issue where inserting a USB stick before booting up doesn't prompt for a new firmware upgrade.
Fixed the garbled text at the end of the OTA upgrade description.
Fixed the system error caused by frequently plugging and unplugging the USB stick during the USB information extraction process.
Fixed the issue where starting a print from the history record and selecting pre-print calibration doesn't take effect.
Fixed the issue where sending print calibration settings doesn't take effect when starting a print from the slicing end.
Fixed the issue where the printer selects automatic leveling, but the app does not display self-checking.
Fixed the incorrect error code type for codes 560-563.
Fixed the issue where the print calibration option is not fully displayed under Japanese in the file details page.
Fixed the inability to immediately stop when first layer detection is enabled and the first layer is printing.
Fixed the issue of .temp files displaying when exporting files to a USB stick.
Fixed the system error caused by excessive memory usage in the AI lidar point cloud restoration.
Fixed the issue where the motor is not released during the pre-print calibration stage and after stopping the print.
Fixed the issue where the motor is not released after the power-on self-test is complete.
Fixed the issue of text and image overlap on the device binding page.
Fixed the issue where the manual self-check completion pop-up doesn't automatically close after starting a print from another terminal.
Fixed the coordinate over-limit error 2243 when the distance between the nozzle and the hot bed exceeds 10mm after home mis-trigger.
Fixed the issue of the device binding page prompt being blocked during the power-on guide.
Modified WiFi driver to solve the problem of the machine always restarting when users report scanning port 5150.
Fixed the issue where the continue command can still be sent during the first layer pause, causing multiple continues to be issued.
Fixed the error in parsing the duration data of the time-lapse video list.
Fixed the crash issue of the root policy prompt page after the timer ends.
Fixed the occasional issue of keyboard button click events being penetrable.

Firmware Optimization:
Optimized some UI text and UI effects on certain pages.
Increased the opacity of the up and down scroll buttons on the file management page.
Non-CrealityPrint Gcode no longer displays a preview image error flooding effect, restoring the original preview image.
Check for agreement to privacy policy after upgrade and prompt the user.
Optimized the logic of generating time-lapse videos, generating videos longer than 3 seconds, and fixed the issue of the end of time-lapse videos not being fully displayed/too fast.
Modified the file compression method of uploading logs to the server to reduce log upload time.
Optimized ripple optimization function.
Optimized synchronization issue between App and machine firmware.
Optimized the accuracy of AI detection during black material printing.
Added video duration to the screen time-lapse video list.
Optimized the information on the Creality Cloud binding page to avoid system lag caused by multiple manual refreshes.

New Features:
Added foreign object detection to lift the hot bed, to avoid the inability to detect the camera blind spot.
Added AI mode setting, distinguishing between regular and professional; regular face confidence is 62.5, professional face confidence is 57.5.
Support version rollback, different models restrict different minimum versions, K1 Max minimum rollback version is V1.3.1.19 (experimental feature).
Added a way to view the root account password in system settings.
Resetting the factory Creality Cloud will unbind the device by default.
Increased the number of error history records to 500.
Added export log, upload log status, progress.
Support for connecting to hidden networks.
Support for connecting to open networks.

__Reference:__
https://github.com/CrealityOfficial/K1_Series_Klipper/releases/tag/V1.3.2.1
