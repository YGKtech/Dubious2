Dubious2 - Box Controller based on the Fake1 (which is based on the Frame1)

After building my first DIY box controller using the Fake1 model, I liked the concept, but wanted to make a few changes. I did not design this from scratch, I just spent a lot of time dragging around parts in borddy's fake1 model, and immitating his work when I needed to add new geometry.


Here's a list of all the notable adjustments I made:
- 'top homerow' layout on the right hand side (this is becoming popular as it's slightly more ergonomic), also tweaked the thumb cluster geometry to pack the buttons more closely.
- a slightly larger case (so you have room to rest your wrists)
- moved the start button from the middle to the left side (so it doesn't get split, and so L+R+A+Start is easier to input)
- removed the Home/Select buttons (since they aren't used in melee, the only game I'm playing on box)
- added a third button to the left hand thumb cluster (This is specifically for the layout I want to use)
- Added mid-plates to the top & bottom (so it's possible to screw the case together before/instead of gluing.)
- Slightly undersized the bottom plate (to make it easier to fit in, the fake1 model has zero margin between the parts, so you may need to sand them to get the fit right, I shrunk the plate by a fraction of a mm in each direction)
- removed the mounting points for the ModelS control board (since I'm building with a Raspberry Pi Pico)
- Replaced the USB-C port with a 1cm circle cutout, and moved it to the side. (the circle works with a variety of cable options, and the USBC port placement assumed you were using a modelS pcb, which I'm not)


A big thank you to @borddy for making the fake1, and for including the fusion360 file in his upload
Thanks to everyone at the Crane's Lab discord server for their help.

Print settings:
Layer Height: 0.3mm (important, any thinner and the sacrificial bridging in the switch cutouts will get messed up)
Infill: 20%
Cooling: off or low (to avoid warping, ymmv)
Generate support: Yes (in theory it isn't needed for the button holes/ switch cutouts since they have sacrificial bridging, but the overhangs in the top plates where the top-middle piece goes need support)
Build plate adhesion: Brim (to prevent warping, helps with bed adhesion)
Print temperature depends on your printer/filament/etc, I printed at 185*c

For buttons you can use the 20.64mm model included in the Fake1 files, or the 21mm buttons from TheSaltiestSea (https://www.thingiverse.com/thing:4755246), for the the fake1 files came out a bit undersized, but that will depend on your printer and settings.
You could also buy genuine Frame1 buttons, or buy resin cast buttons (there's at least one person selling them in the discord server)