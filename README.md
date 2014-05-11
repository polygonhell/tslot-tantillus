tslot-tantillus
===============

DONOT TRY AND PRINT THIS YET IT IS STILL A WIP, NOT ALL THE FILES HAVE BEEN CONVERTED

Note horizontal TSlot must be 10 mm longer to retain original size account for the offset of the 15mm openbeam rather than 20mm extrusion

i.e. original is 5+20 + 200 + 20+5 = 250mm, openbeam must be 5+15 + 210 + 15+5 = 250mm

Vertical beams extend the length of the case, and are therefore the same length

In my build, I dirlled the ends of the drive rods and couple the XY Motors directly too them. This is only practical if you have access to a lathe. You can choose to use standoffs and a coupler like the 2020 design but you will need to use Rod lengths ~5mm longer than the original 2020 TSlot design, rather than the ones specified here.

- OpenBeam lengths:
     - 8x (Horizontal 210mm)
     - 4x (Vertical 335mm)

- All screws for frame assembly are M3x10mm, you'll need washers om the bolts going into the OpenBeam, I recommend cap head screws as they fit into the recesses provided for the XY Stepper mounts. If you are using the 40 mm standoffs from the original design then it doesn't matter.

- 8mm Shafting
     - 2x SFJ8-170 (8x170mm bearing shafts, same as Tantillus internal XY axis)
     - 2x SFJ8-230 (8x230mm bearing shafts, same as Tantillus Z axis)

- 5/16" Shafting
     - 2x --- TBD EXACT LENGTH 277mm
     - 2x --- TBD EXACT LENGTH 277mm with holes drilled 56.5mm in from each end for a distance of 164mm hole to hole

- Hardware
     - Case assembly 
         - 104 M3x10mm screws - I used pan head, but it doesn't matter
         - 96 M3 Nuts
         - 104 M3 Washers

     - X/Y Stepper Mounting 
         - 8 M3x10mm screws MUST be cap head or button head



Z AXIS NOT YET CONVERTED



T-Slot frame for Tantillus 3D Printer

Initial Version Assumes:

- That you are using the cable version of the Z axis. If you aren't you will need to modify the lower Z adaptor for motor mount holes.
- 40mm standoffs for motor mounts, can purchase at mcmaster or print your own. Use 3x50mm bolts to attach motors.
- Misumi 2020 T-Slot lengths:
     - 8x HFS5-2020-200 (Horizontal 200mm)
     - 4x HFS5-2020-335 (Vertical 335mm)
     - HNKK5-5 (T-Slot nuts)
     - M5 10mm button head screw to affix panels to frame
- 8mm Shafting
     - 2x SFJ8-170 (8x170mm bearing shafts, same as Tantillus internal XY axis)
     - 2x SFJ8-230 (8x230mm bearing shafts, same as Tantillus Z axis)
- 5/16" Shafting
     - 2x 277mm
     - 2x 277mm with holes drilled 56.5mm in from each end for a distance of 164mm hole to hole
- Couplers
     - 2x Aluminum or simlar 5mm to 8mm shaft couplers
- Frame extra STL's:
     - spacers.STL - Motor 40mm standoffs if you want to use printed ones
     - knob_fixed.stl - Collar/manual nob for end of 5/16" rod (Use m3 set screw to hold in place on shaft.)
     - fanmount_fixed.stl x2 - Clips to attach fans to t-slot
     - lcdclamp_fixed.stl x2 - Clips to use as a rest for http://www.thingiverse.com/thing:28767
     - megaholder_fixed.stl - Plate for attaching arduino mega to t-slot
- The following files are provided for convenience:
     - ZlowerbracketfixedMETRIC_fixed.stl - Cable Z bracket modd'ed for M5 mounting (Use M5 16mm and M5 nuts)
     - ZupperbracketfixedMETRIC_fixed.stl - Cable Z bracket modd'ed for M5 mounting (Use M5 16mm and M5 nuts)

BEEFY Z Option:

- Is a more rigid Z axis mounting that has some other advantages such as being able to slide the upper and lower mount around and clamping bar end holders.
- BEEFY Z Printed parts
     - Zlowerbracket_BEEFY.stl - Cable Z bracket modd'ed for M5 mounting (Mounts directly into 2060 T-Slot)
     - Zupperbracket_BEEFY.stl - Cable Z bracket modd'ed for M5 mounting (Mounts directly into 2060 T-Slot)
- Misumi 2060 T-Slot Lengths:
     - 1x HFS5-2060-295 (Vertical 295mm [40mm short of main uprights)
- Misumi 90 degree brackets:
     - 4x HBLFSN5
I'm often in #reprap as goopyplastic if you have questions!
