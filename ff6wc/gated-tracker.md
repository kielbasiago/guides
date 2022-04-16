# FF6WC Gated Tracker Setup
The following guide must be complete in its entirety for the tracker to work: 

## [Setup QUsb2Snes](./qusb2snes.md)
<br>
<br>

# Step 0 - Connect your device to Qusb2Snes
Complete Step 4 in the [Qusb2Snes guide](./qusb2snes.md)

# Step 1 - Open the tracker
Visit https://tracker.kielbasiago.com - It will not work right away, this is expected

# Step 2 - Whitelist the tracker
 **IMPORTANT** You will need to whitelist the browser url before continuining. This can be done in one of two ways:
- In your qusb2snes folder there is a `config.ini` file.
    -  There is a `trustedOrigin` line, update it to use `https://tracker.kielbasiago.com` and `https://kielbasiago.com`
    -  When all is said and done it should look like this:
        - `trustedOrigin=";https://tracker.kielbasiago.com;https://kielbasiago.com"`
- Your first attempt to use the tracker should show you a prompt. Click "Yes" to whitelist it: ![TRUST KIEL](https://kielbasiago.com/assets/3-trust-kiel.png)


# Step 3 - Restart the tracker 
Visit or refresh https://tracker.kielbasiago.com 

<br>

# Step 4 Test Connection
## Successful Connection 
You will see the following if you are successfully connected: ![connected successfully](https://i.imgur.com/MxaWnV6.png)

<br>

## Unsuccessful Connection

 You will see the following if there is an error:
 ![tracker error](https://i.imgur.com/kS0ocIE.png)

This means there was an intermittent error with Qusb2Snes. We don't get much context from it. If you are seeing this ensure steps 4 and 2 are complete.

# Help
Post for assistance in the [FF6WC](https://ff6wc.com/) discord #trackers channel if any issues or questions arise