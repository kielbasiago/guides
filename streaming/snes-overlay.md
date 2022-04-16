# Snes Gamepad Overlay
You can add a Gamespad Viewer (GPV). I've hosted an SNES controller skin that you can use in OBS or wherever.

## Preview
- ![SNES GamepadViewer](https://i.imgur.com/eIqnYu3.png)
- https://i.imgur.com/wdluIWP.mp4
- https://www.youtube.com/watch?v=qwtJUBSsO7A

## Setup and Use
- Add the following link as a browser source
```
https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fkielbasa.s3.us-east-2.amazonaws.com%2Fassets%2Fsnes-gpv%2Fsnes-latest.css
```
- The `p=1` may need to change. This will correspond to the player number in GPV. For example, I must select `Player 2` to access my controller, so I would change it to `p=2` ![selecting player 2](https://i.imgur.com/xWEHJXT.png)

## Known Issues
- I had an issue where the D-Pad was not registering in OBS. It randomly went away after a month. No idea what caused it and I hope noone else gets this.
- Not all controllers map 1:1 with the default GPV mapping. You can update these by doing the following :
    - Open the GPV menu and select "Remap Buttons"![Open the GPV menu and select "Remap Buttons"](https://i.imgur.com/RnuAe2m.png)
    - I have never had to do this myself, so you will have to figure this part out.

## Relevant Links
- CSS
    - https://kielbasa.s3.us-east-2.amazonaws.com/assets/snes-gpv/snes-latest.css
- SNES GamepadViewer URL
    - https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fkielbasa.s3.us-east-2.amazonaws.com%2Fassets%2Fsnes-gpv%2Fsnes-latest.css
