PSK-MQTT
========

Initial flow for pskreport - mqtt flows 

This is an initial node-red (https://nodered.org/) flow which consumes the pskr-mqtt feed
and generates a real-time map of reports. As published, it shows reports
for the grid square IO91, but this is easily changed by changing the topic 
pattern.

A demo is available at http://worldmap.modern-industry.com (most of the time)

The map will be accessible at <your host>:1880/worldmap. Editing the flow is a
<your host>:1880

You will need the worldmap node from https://flows.nodered.org/node/node-red-contrib-web-worldmap


Basic Install
=============
- Install node-red on your machine by following the instructions on the node-red site. It runs on
Windows, Mac and Linux, including Raspberry Pi's.
- Install the worldmap node by
  - selecting 'Manage Palette' from the right hand drop down menu.
  - selecting the 'install' tab and typing worldmap into the search bar.
  - find node-red-contrib-web-worldmap and click install.
- Clone this repo and copy the flow.json to the clipboard.
- Access the import function from the right hand drop down menu.
- Past the flow.json into the text box.
- hit the deply button.
- Enjoy. 
- Or, raise an issue.
