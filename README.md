# ESP-909 Evolution
Building upon Jan Ostman's Arduino IDE drum machine codebase for the ESP8266. <br>
Archive.org link:<br>
https://web.archive.org/web/20190917184506/http://blog.dspsynth.eu/audio-hacking-on-the-esp8266/



The project uses a Wemos D1 Mini (ESP8266) and a 16 port 4067 multiplexer. <br>
Thanks to Jack Wildchurch for the usability emphasis!

Currently - <br>
All 11 TR-909 sounds at 44.1kHz <br>
2 different user creatable patterns at a pot selected tempo <br>
16th's pattern length <br>
Live mode and Record mode  <br>
LED BPM and Live mode indicator <br>
Play/Pause button <br>
Tap tempo <br>
Metronome, with on and off <br>
Pattern Change, on the fly <br>
Pattern Copy, from pattern 1 to pattern 2 <br>
Pattern Chain, add pattern 2 to the end of pattern 1 <br>
Beat delete, by pressing the same drum button at the same pattern location <br>
Swing - crudimentarily implemented with a pot for now. Intention is to follow Roger Linn's % method <br>
Play through - play drum sounds over the top of a pattern, without recording them <br>
Reset button (GND and RST) Surprisingly handy during a session <br>
MIDI Out - Tempo/Start/Stop. Tested using Roland JU-06A and Roland TB-03 <br>
MIDI PPQN change, for devices with different clock timings. <br> 
Also, the drum pads allow playing nearly an octave of notes on a connected device. Handy for things with no keyboard. <br>
84% prog memory used - other old skool drumkits can be exchanged in Drums.h <br>

Fritzing or similar schematic to be uploaded. <br>
A quick guide Manual has been uploaded (to be converted to PDF). <br>
Code is commented. <br>
Demo short track - FirstMIDI.mp3 is a quick demo of the sound of ESP-909, straight after getting MIDI to work. In the track it's controlling a sequence on a Roland JU-06A. Recorded live to a Zoom R8 with no EQ. Synth line - Korg X5DR  :)

<br><br><br>

<img src ="./IMG_3746.JPG" raw=true />


