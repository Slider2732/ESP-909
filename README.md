# ESP-909 Evolution
Building upon Jan Ostman's Arduino IDE drum machine codebase for the ESP8266. <br>
Archive.org link:<br>
https://web.archive.org/web/20190917184506/http://blog.dspsynth.eu/audio-hacking-on-the-esp8266/ <br>

Download ESP-909.zip for the ESP8266 and Arduino code <br>
Download Drum Machines.zip for various alternative sample sets <br>
The 3 branches of the project contain this main code page, a builds area and a sound demo's area.
<br>

The project uses - <br>
Wemos D1 Mini (ESP8266) <br>
16 port 4067 multiplexer <br>
MAX98357A DAC <br>
Any Arduino (for handling MIDI messages) <br>


Currently - <br>
All 11 TR-909 sounds at 44.1kHz - and many other classic drum machines can be added <br>
2 different user creatable patterns at a pot selected tempo <br>
16th's pattern length <br>
Live mode and Record mode  <br>
LED BPM and Live mode indicator <br>
Tap tempo <br>
Metronome, with on and off <br>
Pitch shifting, on the fly <br>
Pattern Change, on the fly <br>
Pattern Copy, from pattern 1 to pattern 2 <br>
Pattern Chain, add pattern 2 to the end of pattern 1 <br>
Pattern Save and Load - saving up to 4 drum sounds, per step, on both patterns! <br>
Beat delete, by pressing the same drum button at the same pattern location <br>
Swing - crudimentarily implemented. Intention is to follow Roger Linn's % method <br>
Play through - play drum sounds over the top of a pattern, without recording them <br>
Reset button (GND and RST) Surprisingly handy during a session <br>
MIDI Out - Start/Clock/Stop. Tested using Roland JU-06A, Arturia MicroBrute, Roland TB-03, BOSS DR-550 and more<br>
MIDI PPQN change, for devices with different clock timings. <br> 
<br>
Other old skool drumkits can be exchanged in Drums.h <br>


More drum kits - Drum Machines.zip <br>
It contains replacement Drums.h files for TR-909, TR-808, TR-727, TR-707, TR-606, Drumtraks, DMX, CR-78 and LM-1 <br>
Fresh additions - Drumulator, SP-12 and a Ludwig vintage real drumkit!
<br>
<br>
Fritzing or similar schematic to be uploaded. <br>
A quick guide Manual has been uploaded (to be converted to PDF) <br>
Code is commented, with full connections listed. <br><br>
Demo's can be found in the Sound-demo's Branch - <br>
FirstMIDI.mp3 is a quick demo of the sound of ESP-909, straight after getting MIDI to work <br>
Simulation.mp3 salutes William Shatner's trip into space aboard the Blue Origin spaceship. It uses a TR-808 sample set and no DAC<br>
Various classic machines drum kit examples can also be heard, as implemented on ESP-909 <br>


<img src ="./ESP-909_s.JPG" raw=true />
<br> <br>


Thanks to Jack Wildchurch for the cartridge idea and code testing! <br>
Here is his very cool build of an ESP-909 Evolution<br>
<img src ="./JWbuild.jpg" raw=true />
<br> <br>


