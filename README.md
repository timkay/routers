# routers

The web page http://timkay.com/routers/ scans the local subnet for routers and repeaters. This scan helps you discover the IP address of repeaters, which are often invisible to network discovery tools such as traceroute.

Currently it supports ASUS devices and is known to work with the following products:

* RT-AC68U

# Techical Details

The web page contains JavaScript code that creates &lt;img&gt; tags for the favicon.ico file on each local IP address. If the image loads, then the resulting object is presented better. If the image fails to load, then it is hidden.

The local IP address is determined using WebRTC calls.
