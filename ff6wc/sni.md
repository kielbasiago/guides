**SNI and Tracker Setup**

1. Download SNI here https://github.com/alttpo/sni/releases

2. Run SNI

3. Open up your WC rom on your device
4. Connect your device to SNI

- 4a. **Snes9x-rr**
    -   Open Snes9x-rr and launch the luabridge script.
    - File > Lua Scripting > New Lua Window... 
        - ![new lua window](https://i.imgur.com/HJKlgtC.png)
    -  When selecting lua script, choose `path/to/SNI/lua/x64/Connector.lua` (use x32 over x64 depending on which version of snes9x you are running)

- 4b. **RetroArch**
    - Enable advanced settings by going to `Settings > User Interface > Enable Advanced Settings`
    - Enable network capabilities by going to `Settings > Network` and setting `Network Commands` `ON` 
    - You must use a bsnes-mercury core (@seto did it matter which core you used? retroarch version?)

- 4c. **sd2snes**
    - Will add documentation as needed, reach out if you need help getting this set up so we can get the exact steps
5. Double check connection
- Right click SNI > hover "Devices"
    - If it is connected there should be a `SNI Connector v3` (or something else aptly named)
        - ![sni devices](https://i.imgur.com/z9G4FBj.png)
    - If it is not connected it will be empty
        - ![sni devices](https://i.imgur.com/Gy4u4Ei.png)
- Clicking "Refresh" is necessary when checking for the latest state
