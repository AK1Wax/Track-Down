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
> It is possible to use R4ven for nefarious purposes. It merely illustrates what adept attackers are capable of. Defenders have a responsibility to consider suchattacks and protect their users from them.Using R4ven should only be done with the written permission of the targeted parties for legitimate penetration testing assignments[span_0](start_span)[span_0](end_span).

## Key Features:[span_1](start_span)[span_1](end_span)

- **IP address and GPS location tracking**[span_2](start_span)[span_2](end_span)
- **Collection of device system information**[span_3](start_span)[span_3](end_span)
- **Capturing images from the device's camera**[span_4](start_span)[span_4](end_span)
- **Inbuilt Auto port forwarding**[span_5](start_span)[span_5](end_span)
- **Integration with Discord for data presentation**[span_6](start_span)[span_6](end_span)
- **User interaction for location permission**[span_7](start_span)[span_7](end_span)
- **Display of a website through an embedded iframe**[span_8](start_span)[span_8](end_span)[span_9](start_span)[span_9](end_span)
- **Regular interval-based data collection**[span_10](start_span)[span_10](end_span)
- **Access to and upload webcam images**[span_11](start_span)[span_11](end_span)
- **Links to Google Maps and Google Earth based on location**[span_12](start_span)[span_12](end_span)
- **Error handling for denied location permission**[span_13](start_span)[span_13](end_span)
- **User feedback and error messages**[span_14](start_span)[span_14](end_span)

## On the link click[span_15](start_span)[span_15](end_span)[span_16](start_span)[span_16](end_span)

```diff
+ It will automatically fetch IP address and device information.
! If location permission is allowed, it will fetch exact GPS location.
! If camera permission is allowed, it will capture target pictures.









