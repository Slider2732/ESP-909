# ESP-909
Building upon Jan Ostman's Arduino IDE drum machine codebase for the ESP8266. <br>
Archive.org link: https://web.archive.org/web/20190917184506/http://blog.dspsynth.eu/audio-hacking-on-the-esp8266/


A work in progress - but it does work as a drum machine. <br>
The project uses a Wemos D1 Mini (ESP8266) and a 16 port 4067 multiplexer. <br>
Thanks to Jack Wildchurch for the usability emphasis!

Currently - <br>
All 11 TR-909 sounds at 44.1kHz <br>
2 different user creatable patterns at a pot selected tempo <br>
16th's pattern length <br>
Live mode and Record mode  <br>
LED BPM and Live mode indicator <br>
Play/Pause button <br>
Pattern Change (button on right side end of drum buttons) <br>
Pattern Copy, from pattern 1 to pattern 2 <br>
Pattern Chain, add pattern 2 to the end of pattern 1 <br>
Beat delete, by pressing the same drum button at the same pattern location <br>
Swing - crudimentarily implemented with a pot for now. Intention is to follow Roger Linn's % method <br>
Reset button (GND and RST) Surprisingly handy during a session <br>
MIDI to follow, being worked on for MIDI In and MIDI Out <br>
81% prog memory used - other old skool drumkits are intended to be able to be used in a future update <br>

Fritzing or similar schematic to be uploaded. <br>
A quick guide Manual has been uploaded. <br>
Code is commented. <br>

<img src ="./IMG_3746.JPG" raw=true />


