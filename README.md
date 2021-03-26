# FusionCore
FusionCore is a DIY CoreXY configuration 3D printer with 3 seperate compartments each suited for the components inside it. <br/>
The printer is intended for enthusiests are want to build their own printer while also allowing easy customization in an all in one package. <br/>
Currently, only the CAD model of the printer is implemented. The printer has **NOT** been built yet.

![image](https://i.imgur.com/SSqpXVH.jpg)

**Current Issues with the Design** <br/>
---------------
* Overall dimensions are too big for the 350mm x 350mm x 400mm print bed.
* Screws and nuts are missing from the design. 

**Current Consideration with the Design** <br/>
---------------
* Change tab to handles
* Put handle on the two ends of the middle faces
* Increase Z enclosure hieght height and put filament spools on top. Side filament may reduce torque needed to pull/push the filament trough the extruder, increasing the overall quality and print speeds you can achieve.
* Multimaterial feature?
* Put the fans on the electronics box at the top and bottom vs in the center as I have them right now. Right now, I have what appears to be a pressurized box (one of your fans may be reversed), but nowhere for the air to go. If I blow cool air in the bottom, and suck it out the top, I get much better convective cooling, and I won't get a "hot pocket" at the top where you have no circulation. I started with my electronics on the side like yours, but I found the fans actually pulled a fair amount of heat from the chamber. Moving them to the bottom helped a lot with that.
* duet3D boards running RRF?
* If using endstops, may need to cut off drag pins.
* Plexiglass is acrylic which is technically flammable. Polycarbonate is a bit more expensive, but is flame resistant, has better insulating value, and doesn't require special drill bits. The top, back, and bottom could be made with a single piece saving on cuts.
* You will most likely need to increase the height above the Xbar to clear the bowden and wires for the extruder. I went 12"/30cm on my build, and wish i would have added 2-3"/5-8cm more as it still rubs a bit.250mm is what I would recommend for the minimum. Any less than that and it will curl the bowden down and risks the filament twisting and causing feed issues.
* My chamber is very airtight. Air flowing through the electronics chamber cools the dividing wall and draws heat away. It will do 10-15 degrees Celsius over ambient with just the bed heater. I used a Stego enclosure heater and I easily hit 60C now. These heaters are designed for heating electrical enclosures and work perfectly for our use. Stego 04641.9-00 is the one I used. I got the 24v 250w version, but it was not enough to hit 60c, so I upgraded to the 400w and it hits 60c no problem. They have other models for various mounting locations and types. https://www.stego-group.com/index.php?id=1331&L=316 These can be had on ebay for a fraction of the new price and are often new, unused parts.
* Belts. I wish I had gone with 9-12mm. The 6mm is my current limiting factor.
* Din rails are AMAZING. They make organizing the electronics chamber super easy, and adding things in the future a breeze. A lot of things, like industrial grade power supplies come with din rail mounts built in and can be purchased off ebay for a steal.

**Contributing** <br/>
---------------
Feel free to contact me in regards to how I can improve this prject! For major changes, please open an issue first to discuss the problem!

**License** <br/>
---------------
[GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)