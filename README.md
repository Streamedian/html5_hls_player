## Overview

html5_hls_player.js is a Javascript library which implements HLS client for watching streams in your browser 
that works directly on top of a standard HTML <video> element. 
It requires support of HTML5 Video with Media Sources Extensions for playback. Also player relies on server-side websocket 
proxy for retransmitting HLS streams to browser.

## Test stream

Link to server running with websock_hls_proxy and test page http://specforge.com/html5hlsstream/index.html


Browser support: 

streaming over websocket:
* Firefox v.42+
* Chrome v.23+
* MS Edge v.13+
* Opera v.15+
* Android browser v.5.0+
* IE Mobile v.11+

streaming over HTTP:
* OSX Safari v.8+  
* iOS Safari      

not supported Internet Explorer
