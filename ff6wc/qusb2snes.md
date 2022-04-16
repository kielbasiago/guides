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

5. Visit https://tracker.kielbasiago.com - It will not work right away, that is next

6. **IMPORTANT** You will need to whitelist the browser url before continuining. This can be done in one of two ways:
- In your qusb2snes folder there is a `config.ini` file.
    -  There is a `trustedOrigin` line, update it to use `https://tracker.kielbasiago.com` and `https://kielbasiago.com`
    -  When all is said and done it should look like this: 
```
trustedOrigin=";https://tracker.kielbasiago.com;https://kielbasiago.com"
```
- Your first attempt to use the tracker should show you a prompt. Click "Yes" to whitelist it: https://kielbasiago.com/assets/3-trust-kiel.png

7. Visit https://tracker.kielbasiago.com 

7a. You will see the following if you are successfully connected:
https://i.imgur.com/MxaWnV6.png

7b. You will see the following if there is an error:
https://i.imgur.com/kS0ocIE.png 
This means there was an intermittent error with Qusb2Snes. We don't get much context from it. If you are seeing this ensure steps 4 and 6 are complete.

@Kielbasiago#3699 in the FF6WC Discord #trackers channel if any issues or questions arise