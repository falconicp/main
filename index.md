# Falcon ICP

Falcon ICP is provides a virtual F-16 ICP keyboard integrated with a DED display, allowing to improve your experience with [Falcon BMS flight simulator](https://www.falcon-bms.com/).
It consists of two components:
* Falcon ICP Server application for Windows systems
* Falcon ICP Android application

## Android Application

[![](https://lh3.googleusercontent.com/cjsqrWQKJQp9RFO7-hJ9AfpKzbUb_Y84vXfjlP0iRHBvladwAfXih984olktDhPnFqyZ0nu9A5jvFwOEQPXzv7hr3ce3QVsLN8kQ2Ao=s0)](https://play.google.com/store/apps/details?id=org.bitbucket.falconicp)

The Falcon ICP application can operate in vertical or horizontal orientation.

### Vertical mode

In vertical mode DED is integrated with ICP on one view.

![Main view](images/01_main.png)

### Horizonal mode

In horizontal mode choose between ICP or DED:

<img src="images/02_horizontal_icp.jpg" alt="ICP Horizonal" width="50%">

<img src="images/03_horizontal_ded.jpg" alt="DED Horizonal" width="50%">

### Settings

On the first run the Settings screen opens automatically.
Configure the Server IP address. The default port is 30456.

<img src="images/04_settings.jpg" alt="Settings" width="50%">

## Server application

### Download

Latest release: [Falcon ICP Server v1.0.0](https://github.com/falconicp/main/releases/download/v1.0.0/FalconICPServer-1.0.0.zip)

### Install

The server application is fully portable. Just unpack the zip file and run `Falcon ICP Server.exe`.

### Upgrade

If you have an older version installed, remove all files are unpack the new zip file.

### Setup

1. After starting the application pick the keyfile you use in Falcon BMS
2. Configure keyboard mappings for all ICP buttons
3. Not your server local IP address and configure it in the Android app
4. Click `Start server`. The Android app should now be able to connect.