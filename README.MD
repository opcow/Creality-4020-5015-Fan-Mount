<style>
.indented {
  padding-left: 20pt;
  padding-right: 20pt;
}
</style>
# Ender 3 4010/4020/5015 Fan Mount and Duct
![image](https://raw.githubusercontent.com/opcow/Creality-4020-5015-Fan-Mount/master/view_1.png)

---

### Main Cooling Fan Mount
![plenum image](https://raw.githubusercontent.com/opcow/Creality-4020-5015-Fan-Mount/master/plenum.png)

This part is based on the stock fan cover, but allows the use of a 4020 axial fan on Ender 3 and maybe other Creality printers for heatsink cooling. If using a 4020 fan it must mount on the outside. A 4010 fan should work mounted inside, but I haven't tried it. You can use the stock part cooler or the 5015 bracket and duct with this part (see below).

Parts needed:
* The stock heat sink cooling fan or another 4010 or 4020 axial fan. (The Ender 3 fans are 24v.)
* 2-4 M4 x 15-25mm screws depending on your fan size for mounting the fan. (I only use 2.)
* 4 M3 x 8-10MM screws.
* The original 2 M3 fan cover mounting screws or 2 more M3 x 6mm. If using a socket cap screw for the top bracket slot, a small washer may be needed.
* The original 4 part cooling fan screws or 4 M2 socket cap screws. I believe the stock screws are 2 8mm at the top and 2 10mm at the bottom (where the duct mounts).

Parts to print:

<ul>
<li>plenum_v2.stl</li>
<li>bracket_left_v2.stl</li>
<li>bracket_top_v2.stl or bracket_top_no_slot_v2.stl</li>
</ul>
  I designed this in multiple parts to avoid the need for supports. Print with the fan intake hole down. Be sure to print the left bracket with a flat side down. The non-slotted top bracket can be substitutted for the slotted version. The slotted version provides a bit of adjustment if the fan mount tilt.

Assembly:
1. Mount the top bracket to the fan housing using 2 M3 screws.
2. Mount the left bracket to the fan housing using the 2 stock M3 cover mounting screws or your own M3 screws.
3. If the screw holes are tight you may get bulges around them where the housing mounts to the metal bracket. If so, trim them and any other bumps using a razor of a file, so that the housing will mount flush with the metal plate.
4. Do the following 2 steps in whatever order works best for you. I Installed an inline connector for my 4020 fan, so I install it first and then plug it in as the last step.
5. Mount the fan to the fan housing. Make sure it is oriented so that it blows inward.
6. Mount the stock part cooling fan (don't forget its 90° duct) or the 5015 fan duct to the right side of the fan housing.
7. Mount the fan housing using M3 screws.

---

### 5015 Bracket and Duct
![duct image](https://raw.githubusercontent.com/opcow/Creality-4020-5015-Fan-Mount/master/duct.png)
This part should also work with the stock metal fan cover. 

Parts needed:
* A 5015 centrifugal fan. (The Ender 3 fans are 24v.)
* 3 M2 screws (I used the screws for the stock part cooling fan for this).
* 1 M3 x 6-8mm screw if using the optional bracket.

Parts to print:
<ul>
<li>5015_duct_v2.stl</li>
<li>duct_bracket_v2.stl</li>
</ul>
  No supports are needed for the main part. The optional small bracket should be printed with supports and oriented with the slot facing upwards.

Assembly:
1. If you are using the printed main cooling fan mount, assemble it first as per above, but do not mount it to the printer.
2. Mount the duct to the right side of the main cooling fan box using 3 M2 screws.
3. Mount the entire assembly to the printer.

Optional:

<p class="indented">There is an optional bracket that hooks to the hot end mounting plate. It gives the entire assembly a bit more stiffness. It won't work with the stock metal fan housing and would probably offer little to no benefit anyway.

---