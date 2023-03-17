# -Traffic-Detected-Remote-Unit
"Traffic Detected" Remote Unit for Flightradar24-Feeder

The solution for…:

Problem 1: My FR24-Feeder is mounted far away on my attic. Beside checking the website looking on my radar, I have no control if it works. The "Traffic Detected" Remote Unit signals that the feed to the Server of FR24 is in function by “listening” to the data stream. As long as is “hears” the stream running, the blue LED is on. If anything fails (or there is no aircraft in the remote area) the blue LED is off.

Problem 2: If you live in a “lost” area, there is the chance that you see just some aircraft per day. If you want to know, that there is traffic in your receive area, the blue LED informs you about that.
How does it work?
After connecting to your Wifi (the same network as your feeder is connected to) the unit opens a socket to the IP of your feeder and looks at Port 30003. On this Port, the feeder sends a stream of decoded information of the received ADS-B messages from the aircrafts in the receiving range. As long as this stream is active, the blue LED is turned on. Base for the project is a “ESP32 Wroom” module

What you’ll need

Shopping list

•	1 x ESP32 Wroom module
•	1 x Blue 3mm LED (or any other color) for the LED “traffic”
•	1 x Green 3mm LED (or any other color) for the LED “WIFI”
•	1 x Enclosure by your choice

Tools required

•	Soldering iron
•	Wire cutter
•	Some wire
•	A drill
•	And all the other stuff… depends on your needs

Software required (recommented)
•	Thonny
