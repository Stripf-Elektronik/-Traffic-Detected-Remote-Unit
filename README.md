<p><span style="font-size:11pt"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:22.0pt">&quot;Traffic Detected&quot; Remote Unit</span></strong></span></span></p>

<p><span style="font-size:11pt"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif">For Flightradar24-Feeder</span></span></p>

<p><span style="font-size:10px"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-family:Poppins"><span style="color:#2c2f34">Disclaimer: </span></span></strong></span></span></span></p>

<p style="text-align:justify"><span style="font-size:10px"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-family:&quot;Segoe UI&quot;,sans-serif"><span style="color:#2c2f34">The information provided&nbsp;is for general informational purposes only. While I strive to keep the information up to date and accurate, I make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability with respect to the website or the information, products, services, or related graphics contained on the website for any purpose. Any reliance you place on such information is therefore strictly at your own risk. In no event will I be liable for any loss or damage including, without limitation, indirect or consequential loss or damage, or any loss or damage whatsoever arising from loss of data or profits arising out of, or in connection with, the use of this Information.</span></span></span></span></span></p>

<p><span style="font-size:11pt"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:18.0pt"><span style="font-family:Roboto"><span style="color:black">The solution for&hellip;:</span></span></span></strong></span></span></p>

<p style="text-align:justify"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:13.5pt"><span style="font-family:&quot;Segoe UI&quot;,sans-serif"><span style="color:#2c2f34">Problem 1: My FR24-Feeder is mounted far away on my attic. Beside checking the website looking on my radar, I have no control if it works. The &quot;Traffic Detected&quot; Remote Unit signals that the feed to the Server of FR24 is in function by &ldquo;listening&rdquo; to the data stream. As long as is &ldquo;hears&rdquo; the stream running, the blue LED is on. If anything fails (or there is no aircraft in the remote area) the blue LED is off.</span></span></span></span></span></span></p>

<p style="text-align:justify"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:13.5pt"><span style="font-family:&quot;Segoe UI&quot;,sans-serif"><span style="color:#2c2f34">Problem 2: If you live in a &ldquo;lost&rdquo; area, there is the chance that you see just some aircraft per day. If you want to know, that there is traffic in your receive area, the blue LED informs you about that.</span></span></span></span></span></span></p>

<p><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:18.0pt"><span style="font-family:Roboto"><span style="color:black">How does it work?</span></span></span></strong></span></span></span></span></p>

<p style="text-align:justify"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:13.5pt"><span style="font-family:&quot;Segoe UI&quot;,sans-serif"><span style="color:#2c2f34">After connecting to your Wifi (the same network as your feeder is connected to) the unit opens a socket to the IP of your feeder and looks at Port 30003. On this Port, the feeder sends a stream of decoded information of the received ADS-B messages from the aircrafts in the receiving range. As long as this stream is active, the blue LED is turned on. Base for the project is a &ldquo;ESP32 Wroom&rdquo; module.</span></span></span></span></span></span></p>

<p><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:18.0pt"><span style="font-family:Roboto"><span style="color:black">What you&rsquo;ll need</span></span></span></strong></span></span></span></span></p>

<p><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Shopping list</span></span></span></strong></span></span></span></span></p>

<ul>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">1 x ESP32 Wroom module</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">1 x Blue 3mm LED (or any other color) for the LED &ldquo;traffic&rdquo;</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">1 x Green 3mm LED (or any other color) for the LED &ldquo;WIFI&rdquo;</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">1 x Enclosure by your choice</span></span></span></span></span></span></span></li>
</ul>

<p><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Tools required</span></span></span></strong></span></span></span></span></p>

<ul>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Soldering iron</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Wire cutter</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Some wire</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">A drill</span></span></span></span></span></span></span></li>
	<li><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">And all the other stuff&hellip; depends on your needs</span></span></span></span></span></span></span></li>
</ul>

<p><span style="background-color:white"><span style="font-size:11pt"><span style="background-color:white"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><strong><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Software required (recommented)</span></span></span></strong></span></span></span></span></p>

<ul>
	<li><span style="font-size:11pt"><span style="font-family:&quot;Gill Sans MT&quot;,sans-serif"><span style="font-size:12.0pt"><span style="font-family:Roboto"><span style="color:black">Thonny</span></span></span></span></span></li>
</ul>

<p>&nbsp;</p>

<p style="text-align:justify">&nbsp;</p>

<p>&nbsp;</p>
