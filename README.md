# LRWC
Project:
Long Range Water Cannon (LRWC)
I'm Building A long range, handheld, battery powered water cannon, powered by a high pressure diaphragm pump. The project will include a custom 3D printed body/shell, electronic trigger system.

LRWC will function with a backpack containing a water reservoir. That water will be suctioned from the water reservoir to the pump in a short 3-5 foot garden hose. The pump will then blast the water through a bunch of brass/copper fittings, connecting the pump to a pressure washer nozzle. I chose a pressure washer nozzle since it can be easily swapped for long range and low flow rate, high flow and shorter range ect.
Goals:
 Goal #1:
My primary goal is to design and optimize a battery powered water launcher/gun by experimenting with pump pressure, flow rate, nozzle geometry and plumbing efficiency to achieve a long and consistent stream. My goal for range is 30-65+ feet
 Goal #2:
To learn as much as possible
 Goal #3:
I also want to power the Project with an 18v dewalt drill battery for easy swapping, and since we own multiple at my home. (I will 3D print an adapter and use a stepdown converter/buck converter to get the 12v for the pump) 
 Goal #4:
I am hoping for a 30 minute+ runtime, although if I do not reach that goal, I can easily replace the drill battery so it is not a major concern
 Goal #5:
3D printed and water proof shell to ensure nothing is damaged when enemy fire is returned
 Goal #6:
The water gun should have a 3D printed shell that looks cool

I will use PLA for prototyping, but I will want a stronger filament/plastic such as PETG for the final product with a high infill for decent durability
Past projects:
-Designed and built a custom calculator.
-Built multiple games in Python, Unity, and Godot.
-Designed and printed many multi-week 3D printing projects.
-Currently building an ESP32-based humidity controller with a local web interface for a real client.
-Built my own gaming PC.
-Learned Linux and networking through working with an old server.
-Repaired electronics including an Xbox 360 southbridge reflow
Here I will list a bunch of things and my plans for them:
Frame:
Make some form of strong wooden skeleton and bolt all the parts to it, 2x4 wood or, stacked and glued plywood. I may also use a band saw to make the parts fit nicely
Then I model and 3D print the shell. For extra strength, I will print the final product in a stronger 3D printing material such as PETG in a high infill for added durability (I do not have a printer enclosure or ventilation system so I will avoid plastics such as ABS even if they are technically better)
Trigger:
3D printed trigger held in a stasis by two springs, one on both sides. Cheap momentary switch for a pulling trigger effect. This switch will have a 40a mosfet (the pump is rated for 15) for added safety, and to reduce strain on the switch. The pump will only activate when the trigger is being pulled.
Electronics:
I tried to keep the electronics as simple as possible to make troubleshooting easier and get a working product before I complicate things. Possible additional features such as screens showing remaining water, battery, psi, and electronically controlled nozzle adjustment. Ect

Diaphragm Pump18V Battery
│
Buck Converter (18 → 12 V)
│
├── Pump
│
MOSFET
▲
Momentary switch 

Water:
The water will sit in a large reservoir inside of a backpack. I plan to put it in a backpack rather than the gun, as a large water tank on the gun will be very heavy or have limited ammunition.
The water will be suctioned from the backpack to the pump and then fired through a bunch of fittings into a pressure washer nozzle. I will possibly add a water shutoff valve if there is leaking when I am not using the water gun
Wiring Diagram:
(missing the mosfet, diagram is slightly outdated)

Experimentation:
I expect that the first iterations will not perform as I hope, and I plan to improve based on results
Planned experiments:
-Compare different nozzle orifice sizes
-Test Pump pressures
-Measure stream distance and runtime
-Collect data until I can have the best settings to achieve the maximum range
Inspiration:
I was inspired to build this project when I was helping my friend fix his electric water gun, which was clogged with sand. When we took it apart I realized I could make a much better gun then that and so I began researching. I could not find many cases where people have done this except for a decade old youtube video. That gave me further inspiration, though my design is almost completely different.
Reason:
My reason is that I want to learn. I want to be like the engineers on youtube that make whatever they want. I want to be able to build things myself, and of course, I want to build something that's genuinely cool to use in a water fight.

(this is my first time using hackclub im still trying to figure this out :)
