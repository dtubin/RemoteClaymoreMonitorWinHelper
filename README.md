# RemoteClaymoreMonitorWinHelper
Remote Claymore Monitor - client helper for Windows

RCM.exe is helper app used for Remote Claymore Monitor mobile application. Please download this file and put it directly on rig or if not possible, somewhere else in your LAN.

Example of usage:

1. Create a directory C:\RCM
2. Put RCM.exe in C:\RCM directory
3. Run cmd in search window to get to command line shell
4. Type 'cd c:\RCM'
5. Open your iPhone or Android app and go to settings tab.
6. Take note of your username
7. Type 'RCM.exe -uid USERNAME -desc RIGNAME'
8. If everything is OK you should see output that that confirms successful updates.

- If you receive error that database is not initialized, double-check username provided on mobile app. 
- If your claymore is running on different than port use command line argument i.e. -port 3334 when running the command from line 7.

