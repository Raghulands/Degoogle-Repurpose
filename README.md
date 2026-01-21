Steps To Makeup

1. Prepare the phone
   Enable USB debugging
   Install ADB + Fastboot on your PC

2. Unlock the bootloader
   Reboot to bootloader
   Unlock using Fastboot
   Phone resets

3. Flash a clean custom ROM
   Boot to recovery
   Sideload ROM with ADB
   Reboot (no GApps means no Google)

4. Remove unwanted apps
   Use ADB to uninstall or disable bloat

5. Install your single app
   Push your APK using ADB

6. Make the app device owner
   Use the ADB command to set device owner
   Required for kiosk mode

7. Lock the phone to that one app
   Your app enters lock task (kiosk) mode
   User cannot exit, no home screen, no notifications

8. Set the app to auto-start on boot
   Make your app the default launcher

9. Final test
   Restart phone
   Only your app opens
   Phone works as a dedicated single-task device
