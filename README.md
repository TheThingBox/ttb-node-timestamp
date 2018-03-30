thethingbox-node-timestamp
==========================

A node for <a href="http://thethingbox.io">TheThingBox</a>TheThingBox or <a href="http://nodered.org">Node-RED</a> to add a timestamp to the message.

Install
-------

Run the following command in the root directory of your Node-RED install (TheThingBox : /root/thethingbox/node_modules/node-red)

    npm install thethingbox-node-timestamp

Usage
-----

This node adds a timestamp to the message. It sets msg.timestamp to the current time in UTC ISO 8601 (ex. 2014-09-05T09:02:48.954Z).
