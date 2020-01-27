# SPOUT-VVVV
Spout is a realtime video sharing framework for windows.</br>
In VVVV it allows to stream a texture from one pc to another.</br>
Works better on cable connection instead of WI-fi.


_______________________________________________________________________
<h2><b>Download</b></h2>

<b>1. SPOUT</b> </br>
https://spout.zeal.co/download-spout/</br>

<b>2. SPOUT_TO_NDI</b> </br>
http://spout.zeal.co/download-spout-to-ndi/</br>

<b>3. NDI Tools</b> </br>
https://ndi.tv/</br>

<b>4. vvvv DX11 nodes</b></br>
https://vvvv.org/blog/spout-0</br>
https://vvvv.org/contribution/spout-dx11</br>


<h2><b>Documentation</b></h2></br>

<b>General Spout User Manual</b> </br>
https://spout.zeal.co/download/SpoutUserManual.pdf</br>

<b>SPOUT to NDI Manual</b> </br>
https://spout.zeal.co/download/SpoutToNDI_2005.pdf</br>


<h2><b>Use in VVVV</b></h2></br>

Install Spout and Spout-to-NDI, this last one you can put in any convenient folder.
You must start a vvvv patch sender before opening/starting a vvvv patch receiver.
The order of action is:

ON PC SENDER</br>
1. Start VVVV </br>sender patch (with the node SPOUT sender)
2. Start "Spout to NDI.exe" located in the bin folder of Spout-to-NDI

ON PC RECEIVER</br>
3. Start "NDI to Spout.exe" located in the bin folder of Spout-to-NDI</br>
It should look automatically for available senders. If not choose it from File > Open</br>
4. 1. Start VVVV receiver patch (with the node SPOUT receiver)
