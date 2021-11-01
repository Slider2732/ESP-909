# ESP-909 Evolution
Building upon Jan Ostman's Arduino IDE drum machine codebase for the ESP8266. <br>
Archive.org link:<br>
https://web.archive.org/web/20190917184506/http://blog.dspsynth.eu/audio-hacking-on-the-esp8266/



The project uses a Wemos D1 Mini (ESP8266) and a 16 port 4067 multiplexer <br>
Optionally, a MAX98357A DAC will output crisp clean audio, but also needs an Arduino for handling MIDI messages. <br>
Thanks to Jack Wildchurch for the usability emphasis and code testing!

Currently - <br>
All 11 TR-909 sounds at 44.1kHz <br>
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
Beat delete, by pressing the same drum button at the same pattern location <br>
Swing - crudimentarily implemented. Intention is to follow Roger Linn's % method <br>
Play through - play drum sounds over the top of a pattern, without recording them <br>
Reset button (GND and RST) Surprisingly handy during a session <br>
MIDI Out - Tempo/Start/Stop/Note play. Tested using Roland JU-06A and Roland TB-03 <br>
MIDI PPQN change, for devices with different clock timings. <br> 
Also, the drum pads allow playing nearly an octave of notes on a connected device. Handy for things with no keyboard. <br>
88% prog memory used - other old skool drumkits can be exchanged in Drums.h <br>

Fritzing or similar schematic to be uploaded. <br>
A quick guide Manual has been uploaded (to be converted to PDF). <br>
Code is commented, with full connections listed. <br>
Demo's- <br>
FirstMIDI.mp3 is a quick demo of the sound of ESP-909, straight after getting MIDI to work. <br>
Simulation.mp3 salutes William Shatner's trip into space aboard the Blue Origin spaceship. It uses a TR-808 sample set and no DAC.<br>
A DAC enabled MIDI example is to be uploaded (as of Nov 1st 2021) <br>


<img src ="./ESP-909_s.JPG" raw=true />
