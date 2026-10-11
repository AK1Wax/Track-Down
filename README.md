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

## On the link click
```diff
+ It will automatically fetch...
! If location permission is...
! If camera permission is...
```

## Limitation

```diff
- It will not work on laptop...
# browsers that block javascript
# or if the target is mocking
# or if a target is using VPN

- Some browsers auto block location
+ Location accuracy will be high
```

---

## IP location VS. GPS location

```diff
- Geographic location based on IP
# Does not provide the location accurately
# Instead, it provides the approximate location

+ GPS fetch almost exact location
@@ Once location permission is granted
# Accurate location information is gathered
# (it's almost the exact location)
```

---

### OS compatibility :

---

## Installation

```bash
git clone https://github.com/
cd r4ven
pip3 install -r requirements.txt
python3 r4ven.py
```

`NOTE:` If you're not going to use `localhost`

- choose module(all, cam, ip, gps), open file `index.html` replace `"[http://127.0.0.1:8000/image](http://127.0.0.1:8000/image)"` with the `URL` you wish to use.

OR

Please use the `-t` flag to choose a different URL.

Use the following command to make r4ven executable:

```bash
chmod +x r4ven.py
```

- To change the Image URL use

```bash
python3 r4ven.py [-t target]
```

- To change Port

```bash
python3 r4ven.py [-p port]
```

- For Both Image-URL and port

```bash
python3 r4ven.py [-t target]
```

**Example:** `python3 r4ven.py -t [https://example.com/r4ven/images](https://example.com/r4ven/images) -p 8000`

---

`Enter your discord webhook URL (set up a channel in your discord server with webhook integration)`

[https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks)

`if not have discord account and sever make one, it's free.`

[https://discord.com/](https://discord.com/)

---

📍 *Track info data will be sent to your discord webhook channel.*

- why discord webhook? Conveniently, you will receive a notification when someone clicks on the link.

---

## To change website template

- choose module(all, cam, ip, gps), open file `index.html` replace the `src` in the iframe. (Note: not every website supports iframe)

---

## port forwarding:

- It automatically port forwards with Serveo, but you can choose to use your preferred method for port forwarding.
- The default port is 8000 or any port you specified.

Other cmd to port-forward...
`ssh.localhost.run`

**Serveo:** `ssh -R 80:localhost:8000 serveo.net`

- Make sure you port forward

---

## Mask URL to make it look legit

- Use one of our tools Facad1ng it is An open-source URL masking tool designed to help you Mask URLs and make them look legit using social engineering techniques.

---

## Contribution:

Contributions and feature requests are appreciated. If you encounter any issues or have ideas for improvement, feel free to open an issue or submit a pull request.

---

## 😴🥱💤 ToDo:

- Mask port forwarded URL using our tool Facad1ng
- PHP code to host a website without Python

  https://github.com/spyboy-productions/r4ven/blob/main/snapshots/r4ven-snap.png
