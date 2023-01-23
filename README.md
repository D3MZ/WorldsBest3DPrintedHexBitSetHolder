# The World's Best 3D Printed Hex Bit Set Holder

Lots of 4mm hex bits sockets (135!), and it mounts to your Wall Control Pegboard.
## Good
* Easy to print:
  * Generous tolerance and accuracy of +/- 0.5mm (My Prusa MK3S+ prints at +/-0.2mm) 
  * Only 0.8mm of TPU/E required
* Easy to grab individual bits with fingers due to the generous spacing.
* Easy organizations due to the notches in the design.
* Thin profile that mounts flush with Wall control that feels secure.
* Inserted bits feel stable on insert
* Symetry allows easy expansion (unsure what it looks like on a wall control pegboard)

## Assembly Instructions  

1. Print the Base plate so that it’s facing downwards on the print bed. Two reasons for this:
   1. You’ll get accurate deminsions on the face, which is most important for this model. 
   2. Bridging is invisible to the user since it occurs inbetween the inserted bit and the back of the model
2. (Optional for Wall Control Users) Print the wall control bracket upside down to how you’ll mount it to your Wall Control pegboard. There’s ~215mm^2 of surface area to adhere to the build plate, which should be more than enough for it to stick despite it being a tall thin object.
3. Print the top gripper plate in a high friction soft plastic like TPU/E. With 3.9mm wide hexagons, you’ll end up with 3.5-4mm holes when factoring for printer tolerances and filament shrinkage. Adjust the thickness to how grippy you like it.
4. Glue gripper to base plate
5. (Optional for Wall Control Users):
   1. Insert 4 knurled set screws inside the base print.
   2. Screw the corresponding flat headcap screws (they should be flush with the plastic) connecting the wall control bracket to the base plate.
6. You’re done 😆

## How you can improve this
* Change the holes from hex to circles. It’ll be faster to print, and a reasonable improvement on usability. 
  * Background: I orginally envisioned that a bit would stay in place due to the shape of it. This unfortunately doesn’t work with wide tolerances and hard plastic. The TPU + glue layer is a bandaid that uses friction to grab the bits, but this now makes the alignment requirement between bit and hole a nuisance. 
* Change the size of it so multiple holders can slot into each other on a wall control pegboard. This design most likely produces gaps due to where the mount is placed.
* Parametric variable inputs: 
  * Bit spacing ~= Finger thickness + wiggle room.
  * Size: 
    * This most likely doesn’t fit neatly together on a wall control board, so this will need to be updated.
    * People have different sized drawers / places that they’ll want to dump this into.
* Redesign this for a single material: it’ll be faster, cheaper, more durable, and no glue.
  * If using rubber: TPU/E can probaby be half as thick; but if it’s too shallow, it may not “feel” right, regardless of the physics.
  * Complaince mechanisms: It’ll be great if each bit can click in and out. Try to keep the tolerances to be at least twice worse than what you can print at so others can have simliar success.

## Bill of Materials 
| Name                                    | Description                                                 | Est. Mass (g) | Total $ | Time  |
|-----------------------------------------|:-----------------------------------------------------------:|--------------:|---------|-------|
| Hard Base                               | PETG / PLA                                                  | 131           | 3.67    | 14:11 |
| Rubbery Top                             | TPU/E                                                       | 12.49         | 0.5     | 1:39  |
| Wall Control Mount                      | Optional; PETG/PLA                                          | 6.85          | 0.27    | 0:53  |
| 4 x M2 Bolts (Flat/countersunk headcap) | Optional for Wall Control Attachment; Thread length 4 - 6mm |               | $1      |       |
| 4x M2 Knurled Insert Nuts               | Optional for Wall Control Attachment; 6mm                   |               | $1      |       |
| Plastic to Plastic Glue                 | Superglue works                                             |               | $2      |       |
| Assembly                                | Time to put it together                                     |               |         | 0:30  |
| **Total**                               |                                                             |               | $10     |       |

## Assumptions 
| Name                   | Notes                                          |
|------------------------|------------------------------------------------|
| TPU                    | $40/kg                                         |
| PETG                   | $30/kg                                         |
| Printer Time Estimates | PrusaSlicer 0.20mm Quality Prusa MK3S+ Profile |

[MIT License](https://github.com/D3MZ/WorldsBest3DPrintedHexBitSetHolder/blob/main/LICENSE)
