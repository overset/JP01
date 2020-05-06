==================================
JP01 - Arisu Unibody Keyboard Case
==================================

``[add hero pictures]``

This repository all assets needed to manufacture a custom high-quality CNC milled unibody keyboard case for the open source `Arisu PCB`_. I'm very pleased how the first prototypes came out and I'm documenting the entire process here.

Mission
-------

- Opensource all of my assets and show how "easy" it is to build a custom case in the hopes to inspire more who are interested in the challenge
- Attain a specific aesthetic drawing inspiration from countless custom keyboard case designs from the community, but none of which hit the mark for me
- Build on the opensource `Arisu PCB`_ layout which I find to be close to perfect and build a case that can do it justice. Once I saw the `Arisu PCB`_ layout I knew what I needed to do
- Build the model in the OnShape CAD platform which is completely free for non-commercial projects making this even more accessible to others
- If you order all of the parts at the same time, you can have a fully functioning high-quality custom keyboard in less than a month. No more waiting for a Group Buy, not getting the custom color you want, etc.
- With the first prototype I aimed for a quiet keyboard that still has the best mechanical feel while being silent enough to not be invasive to others yet still a pleasing sound
- Provide not only high-fidelity .STEP model files, but also drawings to accompany them to help ensure you get what you order. Some shops prefer drawings over model files and I'm still stuck on the requirement that the manufacturer should be able to build your product solely from the drawings. My drawings are far from professional quality and I make no claims in being a professional

TL;DR
-----

- | **Cut straight to chase and tell me where the CAD models are!**
  | The models were built using the completely free OnShape CAD platform using the Public plan and available here:
  | `JP01 - CNC Unibody Case - Arisu Keyboard V1.1`_
  | ``TODO: Add assets for manufacturing in releases``
- | **I want to buy this right now, how do I?**

  - First understand the `Risks`_
  - Then jump to `I'm ready, I know the risks, How did I buy this right now?`_


TOC
---

``TODO``


But Why?
--------

There are several prototype cases for the Arisu PCB in the works by some very talented individuals, but the challenge of building one from scratch to meet my design aesthetic was all too enticing.

What I'm looking for in a keyboard and why I think the Arisu layout is a worthwhile investment:

- QMK
- ANSI layout
- Split-fixed with ~18% ergonomic split angle
- Number row is a "must"
- Arrow keys are a "must". No special layers. No HJKL bindings. Just simple, yet present, arrow keys.
- No function rows, I stopped using them long ago
- Less control/super/alt modifiers

Why OnShape and not Solidworks, Fusion360, etc.?

- It's completely free
- It's parametric CAD
- It's feature rich and easy to use with a short learning curve
- I have not found any missing functionality I thought I would need in the modeling of this case
- The Drawings interface is very powerful
- You can fork my design and change whatever you want
- Did I mention it's completely free?


Specifications
--------------

- | **Unibody case**
  | No ugly seam to look at. Minimal fillet and small radii for a specific aesthetic. Simpler design to limit the number of individual parts to get CNC milled.

  - 6061-T6 Aluminum
  - Bead blasted with finer #150 grit
  - Anodized matte finish
  - Color: RAL 7024 (Graphite Gray)
  - No special masking but instructions for not anodizing threaded holes on drawings
  - Threaded holes for base plate and switch plate all M2.5x0.45 with anotation included in Drawings

- | **Dimensions**
  | 359mm wide, 142mm deep, 31.9 mm high on back, 22mm high on front
  | This is Very similar to stock Arisu case
- | **Weight** ~4lb
- | **Typing angle** 5 degrees
- | **Flat baseplate**
  | Original design is for a flat base plate that is slightly recessed into the case. I have incorporated my logo into the design with a 0.5mm depth and a 0.25mm fillet on the top edge

  - 6061-T6 Aluminum**
  - Smoothed surface**
  - Anodized glossy finish
  - Color: RAL 7001 (Silver Gray)
  - No special masking but instructions for not anodizing threaded holes on drawings
  - 4 through bolts to mate plate to case with for M2.5x0.45 countersunk screws

- | **Switch plate**

  - Top mount
  - Allows for 1.6mm to <4mm plate material
  - 8 through bolts to mount the plate to the top of the case, M2.5x0.45 head cap screws

- | **Deck height**

  - 7mm (height from top of switch plate to top of the case)
  - Allows for use of 0.5mm silicone gasket that will make deck-height the ideal 7.5mm to submerge standard keycaps and create a nice aesthetic
  - Easy access to mounting screws to easily change out switch plates

- | **Gaskets** (Optional)
  | These are optional but I designed them to help with acoustics with the priority on silencing. I'm still experimenting with the multiple gaskets, switch plate metals and switch+keycap combinations.

  - 0.5mm Switch plate gasket between case top and switch plate top. This will recess the switch plate down to hit the ideal 7.5mm depth.
  - 2mm or 3mm EVA Foam or 0.5mm silicone PCB gasket to place between the PCB and switch plate to help dampen sound
  - 2mm EVA foam to fill the case cavity between the top of the base plate and bottom of the PCB
  - 1.5mm silicone gasket to seal entire inside surface of bottom plate to reduce reverberation inside the case. This helps the base plate protrude to create a better aesthetic at the expensve of making the whole case 1.5mm taller


Risks
-----

- Ordering completely custom CNC milled parts in low quantities is expensive but not as much as you might think comparing to modern group buys
- You will be managing orders from multiple manufacturing vendors so choose your vendor wisely
- I provide no warranty or guarantee that you will received exactly what was designed here from whichever vendors you choose. I will not be liable for any claims or damages.
- If you modify the CAD designs, you will need to know what you're doing.
- The quality of the final product is as much the manufacturer chosen as it is the original design. Choose wisely


Inventory - What You Will Need To Order
---------------------------------------

- `Arisu PCB v1.1`_
- CNC milled unibody Case, step files and drawings
- CNC milled bottom plate, step files and drawings
- laser-cut switch plate, DXF files
- machine cut gasket kit for sound dampening (optional)
- 4x M2.5x0.45 10mm stainless steel countersunk screws (I prefer hex)
- 8x M2.5x0.45 6mm stainless steel head cap screws (I prefer hex)

I'm ready, I know the risks, How did I buy this right now?
----------------------------------------------------------

``TODO``
  - First understand the `Risks`_
  - find vendors
  - example ordering flow with selected vendors

Show me the build!
------------------

``TODO``

I want to make changes to the case!
-----------------------------------

``TODO``
- HOWTO navigate parts, assembly and drawings
- Want to change the typing angle?
- How to extract specific assets for manufacturers
- Example export of assets

FAQ
---

- | **Again, Why?**
  | I really like the Arisu layout and there is no easily accessible high quality case available for it that meets the aesthetic I was looking for or is something that would be attainable without waiting months if not years. Also: the challenge of building a custom case from scratch
- | **Again, Why the Arisu?**
  | I think the layout is perfect. Having invested a great number of years on fixed-split keyboards such as the classic MS4K, the Arisu layout speaks to me
- | **Is it true designing a PCB is harder than the case?**
  | I think this is true. I applaud those who pour countless and thankless hours over PCB designs. It's a shame most of their work is hidden away inside the case and quickly taken for granted. Even with a clear case it's hard to admire all of their hard work. That and the massive effort behind QMK over the years is awe inspiring and many take it for granted (myself included)
- | **Why not build another Alice clone case or buy one of r/mm?**
  | None of the recent GroupBuys for custom Alice-clone cases have really hit the mark for me aesthetically. I have no doubt the build quality on some, if not all of them, far exceeds this - but the recent surge of interest has made access to join GBs prohibitive. The more recent Prime_E and Rukia come to mind and look amazing. When getting into that price point I'm looking for very specific things such as: a number row (which the Prime_E doesn't have but the upcoming PrimeKB Meridian will have), Arrow keys are a must (not on the Alice or Rukia and no number of custom layers or HJKL bindings are going to save that for me)
- | **RGB?**
  | No, No and No
- | **But it's not symmetrical, why waste your money?**
  | This actually does not bother me at all. Having spend so many years on 75%, TKL and Fullsize keyboards I've always had the majority of keys on the right side. I just expect it and if it's too symmetrical it doesn't feel right to me. Even the Alice is not perfectly symmetrical
- | **When is the GB?**
  | Right now, I do not intend on running a GB myself. I'm licensing the work here in a way that does not prohibit it. If you want to run a group by or one on derived work and use OnShape do consider their ToS. Also, add a reference for this and the amazing work from FateNozomi for the original Arisu keyboard. I'm happy to consult as my time allows on derivative work - it's at the heart of opensource after all
- | **Any modifications required to the Arisu PCB?**
  | None. This is designed around the stock Arisu v1.1 PCB.
- | **Will you sell me one for $100**
  | No
- | **How much will this cost?**
  | Low volume CNC work is cost prohibitive, but not astronomical. This varies greatly depending on manufacturers selected, finishes chosen, etc.
- | **Where is the wrist rest?**
  | See `TODO`_


TODO
----

- Wrist rest! I have a stacked acrylic prototype that I'm already using and love. I have a design for laser-cut solid maple with a leather top to fit perfectly with the case design. I might consider a solid polycarbonate version in the future similar to many other designs I've seen in the community and update this project appropriately
- CNC simplification and cost cutting

  - Reduce reliance on microtooling such as larger fillets
  - Larger radii of inner cutouts in the case - they're likely less than the standard 1/4 diameter of main cutting tool
  - More consistent fillets and radii to minimize different bits or bit changes

- Add more through bolts to the base plate for an even more secure design. The 4 bolt pattern is still more than enough
- Consider raising the deck height of the top of the case from 7mm to 7.5 to account for proper clearance of standard keycaps. The 7mm design was originally built to incorporate a 0.5mm silicone gasket to help dampen sound, but this might not be desirable for some.
- Make the USB port hole a little more centered and the access hole smaller. Possibly add a chamfer, fillet, etc to the USB port more visually appealing
- Experiment with adding more material to the baseplate to bring it parallel with the PCB and minimize the volume of open air inside the case. The intent would be to benefit acoustics and add more weight to the keyboard. I'm very satisfied with the gasket dampener kit as part of the original design for helping with the acoustics
- Test more base plate materials such as various brass, copper, polished stainless, etc. I've started a new OnShape branch for this at `JP01 - CNC Unibody Case - Arisu Keyboard brass baseplate`_
- Add another switch plate screw near the bottom right corner to prevent extra flex when pressing on the right arrow key. This was not even noticeable with the 1.6mm brass, copper, titanium or 6061-T6 aluminum plates I was testing with but would make it closer to perfect


Credits
-------

This case was inspired by FateNozomi's `Arisu PCB`_ and `Arisu Case` which was inspired by Lyn's EM7 and the fabled TGR Alice. This is referred to as the "open source Alice with arrows" and now with a solid unibody case.

.. _Arisu PCB: https://github.com/FateNozomi/arisu-pcb
.. _Arisu PCB v1.1: https://github.com/FateNozomi/arisu-pcb/releases/tag/v1.1
.. _Arisu Case: https://github.com/FateNozomi/arisu-case
.. _JP01 - CNC Unibody Case - Arisu Keyboard V1.1: https://cad.onshape.com/documents/bcb4cb10db076c215d5ca4fc/v/7ff105b1797076ce3c73421d/e/f137899a1015e62802e
.. _JP01 - CNC Unibody Case - Arisu Keyboard brass baseplate: https://cad.onshape.com/documents/bcb4cb10db076c215d5ca4fc/w/63b0d2c4951fb2905cf2d82a
