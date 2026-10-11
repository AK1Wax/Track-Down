# Track-Down
Track the GPS location of the user's smartphone or PC and capture a picture of the target, along with IP and device information.

The tool hosts a fake website which uses an iframe to display a legit website and, if the target allows it, it will fetch the Gps location (latitude and longitude) of the target, capture multiple pictures of the target along with IP Address and Device Information. 

> [!IMPORTANT]
> This tool is a Proof of Concept and is for Educational Purposes Only.
> 
> Using this tool, you can find out what information a malicious website can gather about you and your devices and why you shouldn't click on random links or grant permissions like Location to them.

> [!CAUTION]
> Please use this responsibly and ethically.

> [!WARNING]
> **DISCLAIMER**
> 
> It is possible to use R4ven for nefarious purposes. It merely illustrates what adept attackers are capable of. Defenders have a responsibility to consider such attacks and protect their users from them. Using R4ven should only be done with the written permission of the targeted parties for legitimate penetration testing assignments.

## Key Features:

- IP address and GPS location tracking
- Collection of device system information
- Capturing images from the device's camera
- Inbuilt Auto port forwarding
- Integration with Discord for data presentation
- User interaction for location permission
- Display of a website through an embedded iframe
- Regular interval-based data collection
- Access to and upload webcam images
- Links to Google Maps and Google Earth based on location
- Error handling for denied location permission
- User feedback and error messages.

- ## On the link click

> + It will automatically fetch IP address and device information.
> ! If location permission is allowed, it will fetch exact GPS location.
> ! If camera permission is allowed, it will capture target pictures.

## Limitations

> - It will not work on laptops/desktops without a webcam or GPS module properly configured.
> # Browsers that block JavaScript won't execute the script.
> # If the target is mocking location/IP or using VPN/Proxy, data may differ.
> 
> - Some browsers auto block location and camera permission prompts.
> + Location accuracy will be high if GPS is enabled on mobile devices.

