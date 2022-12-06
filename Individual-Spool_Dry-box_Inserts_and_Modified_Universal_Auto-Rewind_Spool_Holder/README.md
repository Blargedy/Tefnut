Need to move your spool of filament into a dry-box while still using the Universal Auto-Rewind Spool Holder? This set of files will let you do so. This set of modifications and new custom parts moves VincentGroenhuis' rewinder into a [Rubbermaid 1776473 21-Cup Dry Food Container](https://www.amazon.ca/Rubbermaid-1776473-21-Cup-Food-Container/dp/B003EYUZJU/ref=sr_1_1?dchild=1&keywords=rubbermaid+21+cup&qid=1617937803&s=kitchen&sr=1-1). When combined with a panel mounted pneumatic fitment or mmu tube holder you can print directly from this dry-box.

The old container I made this for originally is no longer available so I updated the version in the link above. Use this [better axle](https://www.thingiverse.com/thing:4324181) remix made by [itnaanti](https://www.thingiverse.com/itnaanti/designs).

For keeping a set of dry-boxes on top of the [mmu compatible printing enclosure](https://blog.prusaprinters.org/mmu2s-printer-enclosure/) see the [dry-box holder](https://www.thingiverse.com/thing:3867177), specifically designed for the Rubbermaid container used. Five of these holders are required, as well as 470 cm of new longer and wider tubing. The new tubing is 4mm inner diameter (ID) and 6mm outer diameter (OD), from now on called 4 ID/6 OD tubing.The lengths to cut are:

* 4x 90 cm
* 1x 110 cm

If you value symmetry over minimum tubing length you can use a 3-in-the-front-2-in-the-back pattern and cut a 90 cm piece to 110 cm instead. This will give a total tube length of 480 cm. 

### NB: due to the increased length of tubing required to use these containers on top of the printer enclosure, using the same 2 ID/4 OD tubing the mmu came with, but cut longer, will not work. The friction introduced is too high and will cause frequent jams, especially during filament unloads. 

This is due to the slight deformation of the filament by the bondtech gear during unload being too much if there is already friction from 90cm of tubing. Previously I used very short lengths of 4 ID/6 OD tubing, but the reverse torque of the rewinders pulled the filament out of ready-to-load position. Now however the 90cm of tubing is enough friction to prevent the rewinder pulling the filament out, but low enough to feed beautifully. I've had no load/unload issues since switching to the high diameter tubing. 

In order to use 4 ID/6 OD tubing you'll need a [push-to-fit PTFE holder](https://www.thingiverse.com/thing:3812486) to replace the bracket at the back of the MMU. If you instead want to use PC6-M10 pneumatic fittings see the [source file](https://www.thingiverse.com/thing:3233579) I used to remix my version. The pneumatic connectors can be bought inexpensively from ebay, if you're willing to wait a couple months to get them. The tubing can be bought most easily from [McMaster-Carr](https://www.mcmaster.com/3295n6) at $0.55USD/foot

A further issue that may arise due to usage of these dry boxes is a back heavy enclosure lid. If you are careful it is not an issue, but it may happen that when you open the lid too far it flips past the axis of rotation to the other side and crashes all of the dryboxes to the ground and breaks the hinges. However fear not, I have experienced this failure on your behalf, and designed a [part](https://www.thingiverse.com/thing:3958071) to prevent this from happening to you. 

The tube holders at the top of each dry-box are found [here](https://www.thingiverse.com/thing:4918785)

#### Change log
#### v1.1 Sept 16 2019
* remove square boss on both sides
* thin roundEndAxleHolder container-side wall by 1mm
* thin roundEndAxleHolder inside-facing wall by 1mm

#### v1.2 Sept 18 2019
* deepen counter-bore for bolts to avoid snagging on auto-rewind dial
* thin holders to make space for larger spools

#### v1.2 Nov 1 2019
* tighten hex nut counter-bore to prevent spinning of nut. Previous nut version was v1.1
* Add 3mf export from solidworks

Use PETG if at all possible, as the parts are quite small and need to be functional strength.

NB: the parts are very thin, so wait until they are completely cooled off before removing them from the bed, or risk warping them. 

Print the inserts lying flat, except for the slotted insert, which should be printed with the opening facing up with supports under the slope if you so desire. Use the provided 3mf file to get an example selection and layout which can be modified.

Warning: the spring is very difficult to get to stay on the plate and not ruin a print. I therefore recommend printing it separately so it doesn't ruin a 16h print with its 4-5 retries before the plate is sticky enough to have it succeed. 

#Parts to Print#

## From Original
* Curved nut (regular or XL)
* Spring flat
* Dial
* Clutch
* Clip

## From This Set
* One of each STL in the base folder
* One extra Axle Holder Nut

#### Tips for installation
* Mark or make note of the end from which you measured the 110mm as the location will be off by 5mm if you don't use the same edge when marking the holes for the other sides' holders. 
* Drill on low speed or you might crack the plastic, as it seems to be PC. 
* Use a razor scraper to trim off the drill burs.
* Use socket head M3x10 spare bolts from the prusa kit, and the corresponding hex nuts to attach the inserts. 
* Use only a single curved nut to attach the spool onto the rewinder hub. 
* For v1.01 springs make sure the spring/clutch/dial assembly is on the right side, looking at the back of the dry-box.
* Assemble the rewinder using the instructions from the original rewinder by VincentGroenhuis.

#### Instructions
1. Drill the holes in the measured locations shown in the picture above.
2. Using the same drill bit, pre-drill the holes of the four insert pieces to allow the bolts to pass easier.
3. Put two M3x10 bolts into the holes of the slotted end axle holder's two holes, pushing them most or all of the way through.
4. Reach inside the container and, making sure the open end of the U shaped holder is facing towards the opening of the container, push the two bolts out through the holes of the dry-box. Pushing the bolts through as far as possible makes the next step easier. 
5. Keeping one hand inside the container with fingers on the bolts, turn the container onto it's side with the bolt-protruding side facing up.
6. Place one axle holder nut over the protruding bolts and push the bolts up through the holes as much as possible.
7. Place two hex nuts into the hexagonal counter-bores on the two holes. 
8. If possible, turn the bolts with your fingers to get at least one rotation of purchase on the threads of the nut.
9. Using a 2.5mm hex key (if you used the prusa spare hardware), tighten the bolts evenly until they are fully tight. The head of the bolt should sink into the counter-bore with a little bit of the top poking out. 
10. Repeat steps 3-9 with the round end axle holder and remaining axle holder. The bolts will sink further into the part than the surface of the part. 
11. Install your preferred panel-mounted tube feed-through, and insert one of the PTFE tubes from the MMU into it. 
12. Lower the assembled spool holder and spool contraption into the dry-box. If you are using the v1.01 spring, put the spring side on the right when looking from behind, with the spool delivering filament from the top of the spool. The spring should be on the left if the spool is delivering filament from the bottom of the spool. 
16. If desired, put desiccant into the bottom of the dry-box, close the lid and you're rockin'.

The problem that arises by switching to larger tubing is that the 1.75mm filament gets stuck  on the lip of the mmu right before the bondtech gears. There are fancy adapters you can buy or print, but no need, this way works better, doesn't need new hardware, and works with the stock mmu tube holder, my 6mm OD [push to fit plate](https://www.thingiverse.com/thing:3812486), or PC6-M10 connector plates. In the pictures I used my push to fit plate. 

It is recommended to first install the [drybox holders](https://www.thingiverse.com/thing:3867177) before installing these tubes. More on that later. 

1. Install the mmu tube-holding plate of your choice.

2. Using the recently discarded smaller 2 ID/4 OD tubing from the mmu, cut five lengths of tubing, each 5mm long.

1. Using an Xacto #11 blade or similar, cut a 45 to 60 degree chamfer to the inner lip of one side of each tube length. The steep angle of the blade makes it so you can tilt the blade to one side then spin the tubing around and scrape/cut the inner chamfer to the right amount. 

4. Taking the 5 chamfered tubes, insert them in to the mmu back plate WITH THE CHAMFERED SIDE FACING OUT. Wiggle and push them to make sure they are all seated as far as they will go. 

5. Cut the 4 ID/6 OD tubing to length, either 4x90cm & 1x110cm, or 3x90cm & 2x110cm. 

6. Using the xacto knife chamfer the inner edge of the opening on one side of each tube length. 

7. Mark out five dots on the back acrylic panel: 28cm up from the bottom edge, 2cm apart, centered on the panel. 

8. Using a sharp 8mm drill bit, on SLOW SPEED, drill the five spots you marked. 8mm is enough to give friction so things don't wobble around, but leaves enough play to attach the tubes and move the printer. (Learn from my mistakes and drill slowly)

9. Chamfered end first, insert the 4 ID/6 OD tubing through the holes, and hook the straight cut end of the tube into the empty dry-box holder. The stiffness of the tubing will hold it in place until you attach the tubing to the drybox. Make sure to put the 110cm long length(s) of tubing in the correct hole corresponding to the further back drybox holder(s).  

10. Carefully guiding the larger tubing over the smaller tubing, push the larger tubing all the way to the MMU plate. If the smaller tubing didn't get stuck in the tubing you can push hard to firmly seat the larger tubing into the push to fit plate or festo fittings. If you can't get the larger tubing into the plate it isn't a big deal as the smaller tubing is connected and will guide the filament in. 

12. Attach the dryboxes to the enclosure lid, and connect each tube to its box. 

11. Try loading filament on each lane to test if the chamfers cut on the smaller tubing is enough to prevent the filament from getting stuck, and to see if the small tubing is seated correctly. Rechamfer/reseat as required
