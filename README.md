# HPA-Silly-Shell-Shotgun-SMG
A Silly Shell SMG powered by compressed air. Cosmic Nomad HPA core/dump tank.

https://www.youtube.com/watch?v=duaTlLghZCg

The blaster is in a really good spot functionally and design-wise right now! Idk if I'll ever finish it myself due to time, so I've put the most up to date files (12-30-2025) on GitHub.

All that needs to be done on the blaster:
- Make the attachment from the pneumatic cylinder to the bolt better. Maybe screw the cylinder's rod into a separate print, which then itself is pinned or held in with an m3 screw (with a heat set insert on the other side for removability for servicing).
- Switch the magazine and magwell to the one used on the new box magazine shotgun blaster.
- Make proper structural elements for the blaster. As it is currently modeled, there is just temporary threaded rod holes willy-nilly across the sides of the blaster to hold it mostly together. You should redo those with better positioning and better lengths (use the same length rods as the Breacher?). 
- Use a grip without those grip scales on it. The grip scales that use the tiiiiiiiiiny little screws are a bit of a pain. Not really worth it IMO. 
- Consider switching to a purely pneumatic firing system for the HPA stuff. AKA, use an MJVO-3 or something similar, instead of the current electrically operated solenoid valve. 
- The normal tolerancing and assembly process improvements across the blaster. Nothing major.
- Right now the bolt is moved back and forth by elastic wrapped around it on the outside lol. Figure out a better place to put that elastic (maybe inside the blaster behind the bolt? Maybe put a spring there instead? Both are good options IMO.)

THAT'S PRETTY MUCH IT!



More info: 

- The blaster uses a Cosmic Nomad HPA core by Roboman. You could very easily change the system to use pretty much any HPA dump tank/core, just change the mounting bracket for the tank and have it output air to the same location.
- The blaster uses a solenoid valve, same as the one I use in the HPA Thing and the Twister HPA bullpup. TAILONZ PNEUMATIC 1/8"NPT Solenoid Valve 3V110-06 DC12V Single Coil Pilot-Operated Electric 2 Position 3 Way Connection Type (Outlet wire) https://www.amazon.com/dp/B0BWDSJCCS
- The blaster uses a pneumatic cylinder to cycle the bolt to eject and chamber shells. The cylinder is: Air Cylinder CDJ2b16-100S Single Acting.
- As the blaster is built currently, with the electric solenoid valve for firing, the blaster is 100% compatible with the same smart electronics as the HPA Thing and the Twister HPA bullpup. You can use the exact same Xiao (or similar) microcontroller board to do full auto, semi auto, burst fire, etc etc. Just adjust the timing of each shot more, because this blaster has a lot more stuff moving during each shot. It takes more time for each shot to fully cycle. 
