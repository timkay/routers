# routers

This web page will scan the local subnet for routers and repeaters. Currently it supports ASUS devices and is known to work with the following products:

* RT-AC68U

# Techical Details

The web page contains JavaScript code that creates <img> tags for each local IP address. If the image loads, then the resulting object is presented better. If the image fails to load, then it is hidden.

The local IP address is determined using WebRTC calls.
