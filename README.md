This is a 30x35 mm PCB design in Kicad. 2-layer board. It's a basic board with a 10 pin header on the edge.

A nice size for experiments. Plugs vertically into a solderless breadboard.  

Outline was inspired by https://github.com/OLIMEX/BB-CH340T

Layout notes for 30x35 Outline

-- Trying to follow JLCPCB https://jlcpcb.com/ 2-layer design rules -- (have not fabbed yet)

-- KiCAD PCB design template --

1. Back Copper plane is GND net, 45 deg hatch, 0.25 mm (10 mil) stripe, 0.75 mm (30 mil) gap
2. Layers renamed:  Front -> F.Cu, Back -> B.Cu, Silkscreens -> Silks
3. Track width 1.0 mm (39 mil) defined.
4. Via with 1.0 mm annular and 0.5 (20 mil) hole defined.
5. Minimum text thickness constraint set to 0.16 mm
6. 2-sided rules, 1.6 mm thick board, 35 um (1 oz) copper foil
7. Solder mask and paste rules all zero
8. Minimum via hole and drill 0.3 mm, min pad diameter 0.5 mm
9. Hole to hole clearance 0.5 mm
10. 10 pin RA header, P1, 2.54 mm pitch, 1.0 mm holes, ends connected to GND net
11. 3 Fiducials on front copper
12. Board outline 30 x 35 mm with chamfered corners.
13. Libraries modified for better silk-screen visibility
14. P1 header footprint is outside of Edge.Cuts. The physical part is off the edge.

![30x35_outline2f](https://github.com/bobu01/30x35_outline/blob/main/30x35_outline2f.jpg)
![30x35_outline2b](https://github.com/bobu01/30x35_outline/blob/main/30x35_outline2b.jpg)

![Screenshot_2024-06-25_21-37-51](https://github.com/bobu01/30x35_outline/assets/92656071/4345aeee-d3de-411c-95e7-96fa2977106c)
