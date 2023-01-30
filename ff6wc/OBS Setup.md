
# OBS Browser Source Setup for FF6WC Tracker
This is a guide for configuring a browser source in OBS for use when recording and/or streaming. It provides instructions for:
1.  [Creating a browser source](https://github.com/Javinat0r/guides/edit/patch-1/ff6wc/OBS%20Setup.md#create-a-browser-source-in-obs)
2.  [Setting up tracker with full header](https://github.com/Javinat0r/guides/edit/patch-1/ff6wc/OBS%20Setup.md#set-up-browser-source-with-full-ff6wc-header)
3.  [Setting up tracker with logo header](https://github.com/Javinat0r/guides/edit/patch-1/ff6wc/OBS%20Setup.md#set-up-browser-source-with-ff6wc-logo-header)
4.  [Setting up tracker with no header](https://github.com/Javinat0r/guides/edit/patch-1/ff6wc/OBS%20Setup.md#set-up-browser-source-with-no-header)
5.  [Description of the different CSS options](https://github.com/Javinat0r/guides/edit/patch-1/ff6wc/OBS%20Setup.md#css-option-descriptions)

## Create a Browser Source in OBS
Create a browser source in OBS by:
1.  Right click on the sources tab.
2.  Mouse over "Add..."
3.  Left Click on "Browser"
See the image below:
![Create Browser Source](https://i.imgur.com/5uNzsQr.png)

## Set up Browser Source With Full FF6WC Header

![Tracker with Full Header](https://i.imgur.com/NyICLqQ.png)

1. Right click on the new browser source you have created and select "Properties" at the bottom of the list.
2. In the Properties window, fill out the fields and select the options as listed here:
```
  URL: https://tracker.ff6worldscollide.com
  Width: 650
  Height: 900
  Custom CSS:
    .WC-button { display: none; } 
    .WC-footer { display: none; }
  Shut down source when not visible: Checked
  Refresh browser when scene becomes active: Checked  
```
See the image below for what the settings page should look like:
![Full Header Settings](https://i.imgur.com/Oe5OQAh.png)

## Set up Browser Source With FF6WC Logo Header

[Tracker with Logo Header](https://i.imgur.com/78S57WX.png)

1. Right click on the new browser source you have created and select "Properties" at the bottom of the list.
2. In the Properties window, fill out the fields and select the options as listed here:
```
  URL: https://tracker.ff6worldscollide.com
  Width: 650
  Height: 900
  Custom CSS:
    .WC-button { display: none; } 
    .WC-footer { display: none; }
    .WC-hero { display: none; }
  Shut down source when not visible: Checked
  Refresh browser when scene becomes active: Checked  
```
See the image below for what the settings page should look like:
![Logo Header Settings](https://i.imgur.com/uI0p7Cn.png)

## Set up Browser Source With no Header

![Tracker with no Header](https://i.imgur.com/ZG4OTih.png)

1. Right click on the new browser source you have created and select "Properties" at the bottom of the list.
2. In the Properties window, fill out the fields and select the options as listed here:
```
  URL: https://tracker.ff6worldscollide.com
  Width: 650
  Height: 650
  Custom CSS:
    .WC-button { display: none; } 
    .WC-footer { display: none; }
    .WC-header { display: none; }
  Shut down source when not visible: Checked
  Refresh browser when scene becomes active: Checked  
```
See the image below for what the settings page should look like:
![No Header Settings](https://i.imgur.com/F5ZGhb6.png)

## CSS Option Descriptions

```
.WC-button { display: none; } hides buttons on the screen
.WC-footer { display: none; } hides the footer/shoutout at the bottom
.WC-header { display: none; } hides the entire header (hero image included)
```
If you would like to keep the logo but hide the background of the header you can use:
```.WC-hero { display: none; }``` instead of ```.WC-header { display: none; }```
