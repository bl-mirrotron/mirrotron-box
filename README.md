# The Mirrotron Application Server
* <a href="https://github.com/bl-mirrotron/mirrotron-box" target="_blank">Source code</a>
* [Control system overview](https://docs.bl-mirrotron.com/)

The server for a Mirrotron control system is derived from the Blinky-Lite<sup>TM</sup>Box as shown in Figure 1. The box can be instantiated on a small computer inside a firewall such as Raspberry Pi 3B+ which is more than adequate for a medium size control system or can be hosted  in the cloud.

The primary tasks of the box are to:
* Subscribe to the messages from all of the trays in the system
* Scan each message for alarm notifications and notify alarm system
* Store the latest messages from in the tray database
* Archive a message when appropriate
* Serve applications to users

The box consists of three components that can reside on the same computer or separate (cloud) computers
* Application server
* MQTT Broker
* System database

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 1. </span> <span style="font-style: italic;">Schematic of a Blinky-Lite<sup>TM</sup>Control System</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/BlinkyLiteBox.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 2. </span> <span style="font-style: italic;">Data Logger Flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/dataLogger.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 3. </span> <span style="font-style: italic;">MongoDb Database Flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/MongoDB.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 4. </span> <span style="font-style: italic;">Access Applications Flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/AccessApps.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 5. </span> <span style="font-style: italic;">User Application Slots Flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/Appslots.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 6. </span> <span style="font-style: italic;">Cube Display App Flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/cubeAppLibrary.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 7. </span> <span style="font-style: italic;">Cube App configuration</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/appConfig.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 8. </span> <span style="font-style: italic;">App websocket router</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/WebsocketRouter.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 9. </span> <span style="font-style: italic;">Scalar utility applications flow</span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/ScalarApps.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure 9. </span> <span style="font-style: italic;">Logbook App Flow </span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/LogBook.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure10. </span> <span style="font-style: italic;">Machine Permit Flow </span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/MachinePermit.png"/></div><br>

<p></p><p style="text-align:center;font-size: large;"><span style="font-weight: bold;color: green;">Figure11. </span> <span style="font-style: italic;">Easy Setup Timer Flow </span></p>
<div style="width:100%;text-align:center;"><img width="100%" style="border-style:solid;border-color:#1c6e97;" src="doc/easySetupTimer.png"/></div><br>
