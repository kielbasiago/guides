**Qusb2Snes and Tracker Setup**

1. Download QUsb2snes here https://github.com/Skarsnik/QUsb2snes/releases
   
2. Run QUsb2snes
 -   This may not open a window, but will be available in your tray (near the windows clock)
-   The first time opening it should prompt you to enable a device. In this example I'm using `Snes9x-rr/BizHawk` but you can use sd2snes or retroarch as well.
-   If you select the wrong device, continue with step 3, otherwise continue to step 4
-   ![enable devices](https://kielbasiago.com/assets/1-enable-device.png)

2a. Enable your device in QUsb2Snes
-   Right click the Qusb2Snes icon
-   You may need to do this if you choose the wrong device in step 2 or are connecting to a new device
-   ![select device](https://kielbasiago.com/assets/2-select-device.png)

3. Open up your WC rom on your device
4. Connect your device to Qusb2Snes

4a. **Snes9x**
-   If relying on a lua emulator, launch the luabridge script. (Located in path/to/QUsb2Snes/LuaBridge/luabridge.lua)

4b. **RetroArch**
- Enable advanced settings by going to `Settings > User Interface > Enable Advanced Settings`
- Enable network capabilities by going to `Settings > Network` and setting `Network Commands` `ON` 
- You must use a bsnes-mercury core (@seto did it matter which core you used? retroarch version?)

4c. sd2snes
- Will add documentation as needed, reach out if you need help getting this set up so we can get the exact steps


## Help
Post for assistance in the [FF6WC](https://ff6wc.com/) discord #trackers channel if any issues or questions arise