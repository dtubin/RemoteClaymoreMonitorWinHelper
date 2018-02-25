# RemoteClaymoreMonitorWinHelper
Remote Claymore Monitor - client helper for Windows

RCM.exe is helper app used for Remote Claymore Monitor mobile application. Please download this file and put it directly on rig or if not possible, somewhere else in your LAN.

Example of usage:

- Download rcm.exe and store it anywhere on your hard drive
- Double-click the file to run it
- Scan the QR Code that will be displayed with your mobile app. 
- If successful, app will confirm the match 
- Go to monitor tab, you should already see your Rig data there.

If needed some of argument options can be used:
- If you have more than one rcm process running on your rig: please add -rigid=yourdescription to monitor independently. Example: rcm.exe -rigid=test123
- If automatic process recognition failed for some reason, you can define the port for monitoring rig manually by adding the argument -port=portnumber. Example: rcm.exe -port:3334
- If you have changed username, and want to rematch the rigs to your new Username, please use argument -showqrcode to display the qr code again and connect the rig to your new username. Example: rcm.exe -showqrcode

Please contact us at info@tappicon.com for any questions. We will be glad to assist you and set your monitoring up and running.
