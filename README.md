#Clonos
**Open source network audio player**
by Wouter Devinck

##Repositories
 * **Hardware** (block diagram, schematic, pcb layout, ...): <br />
   https://github.com/wouterdevinck/clonos-hardware
 * Software (QT application, GStreamer interaction, ...): <br />
   https://github.com/wouterdevinck/clonos-application
 * Build system (Buildroot configuration files, kernel configuration, ...): <br />
   https://github.com/wouterdevinck/clonos-build
 * Android app: <br />
   https://github.com/wouterdevinck/clonos-android
 * Efforts to reverse engineer Spotify Connect: <br />
   https://github.com/wouterdevinck/clonos-poc-spotify

##Block diagram
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/blockdiagram.png)

##Prototype
*Status: boards ordered (December 1, 2015)*

Stack of four boards with all the components that have to end up on the final board.

###Protostack CPU
https://workspace.circuitmaker.com/Projects/B66F455D-E0F4-4F57-BF12-8FCD42A89455
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-cpu-pcb.png)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-cpu-front.PNG)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-cpu-back.PNG)

###Protostack Power
https://workspace.circuitmaker.com/Projects/ADCA47EF-8110-4858-A632-40D1FB39EC8E
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-power-pcb.png)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-power-front.PNG)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-power-back.PNG)

###Protostack Audio
https://workspace.circuitmaker.com/Projects/CEEC1620-CD76-49D0-8387-5E8A08206CBC
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-audio-pcb.png)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-audio-front.PNG)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-audio-back.PNG)

###Protostack Wifi
https://workspace.circuitmaker.com/Projects/3BDADFC3-9059-4C72-BE22-5D24FC84C105
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-wifi-pcb.png)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-wifi-front.PNG)
![alt tag](https://raw.githubusercontent.com/wouterdevinck/clonos-hardware/master/images/protostack/protostack-wifi-back.PNG)

##Final board
*Status: board design in progress*
https://workspace.circuitmaker.com/Projects/203E8A99-4B7F-4577-A6F3-57C3B201C072

##License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This **hardware design** is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
