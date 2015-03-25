webrtc-application-screen-share    
===============================

Based on the work of emannion keeping just screensharing aspect.

https://github.com/emannion/webrtc-application-screen-share

![Architecture diagram](https://github.com/emannion/webrtc-application-screen-share/blob/master/arch.png "Arch diagram")


####  Setup prerequesites

- Install Node.js  and  websocket (sudo npm install websocket)

####  Server Steps (Tested on Linux, MacOS and Windows)

- clone this repo to your machine, does not need to be to a web server.
- Edit packaged_app/app.html (insert this machines ip address for WebSocket connection). Or use configure button when running.
- run 'node app.js'  or 'sudo node app.js' depending on your user, try both.

####  Client Packaged App steps (Chrome browser or Chromebook)

- Install packaged app in chrome
- i.e. open 'chrome://extensions'
- click 'Developer Mode' check box.
- Click button 'Load unpacked extension'
- Navigate to the packaged_app folder of this repo
- Launch app by clicking 'launch' link in chrome://extensions
-  Or use Chrome App Launcher to launch it.

####  Client Attendee Web Page Steps 

- Start Chrome or Firefox browser
- Point browser to  e.g. http://\<your node.js ip address\>:1337
- You can test this on the same machine or across the network over two machines.

