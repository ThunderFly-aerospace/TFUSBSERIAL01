# PCB

Board size: 30.0x30.0 mm (1.18x1.18 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness | Material        | Epsilon_r | Loss tangent |
|----------------------|----------------------|------------------|-----------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |           |                 |           |              |
| F.Mask               | Top Solder Mask      | Green            |        10 |                 |           |              |
| F.Cu                 | copper               |                  |        35 |                 |           |              |
| dielectric 1         | core                 |                  |      1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |        35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   | Green            |        10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |           |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |           |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.2 mm (8 mils)

- By design rules: 0.2 mm (8 mils)

Drill: 0.5 mm (20 mils)

- Vias: 0.5 mm (20 mils) [Design: 0.4 mm (16 mils)]
- Pads: 0.65 mm (26 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.8/0.4 mm (31/16 mils)

- By design rules: 0.4/0.3 mm (16/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 71 (thru: 71 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.15 mm (6 mils)

- By design rules: 0.15 mm (6 mils)

Eurocircuits class: 4B
- Using min drill 0.5 mm for an OAR of 0.15 mm


# General stats

Components count: (SMD/THT)

- Top: 0/6 (THT)
- Bottom: 22/1 (SMD + THT)

Defined tracks:

- 0.2 mm (8 mils)
- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)
- 0.6 mm (24 mils)
- 0.8 mm (31 mils)
- 0.86 mm (34 mils)

Used tracks:

- 0.2 mm (8 mils) (34) defined: yes
- 0.3 mm (12 mils) (90) defined: yes
- 0.4 mm (16 mils) (23) defined: yes
- 0.5 mm (20 mils) (36) defined: yes

Defined vias:


Used vias:

- 0.8/0.4 mm (31/16 mils) (Count: 71, Aspect: 2.0 A) defined: no

Holes (excluding vias):

- 0.65 mm (26 mils) (2)
- 3.0 mm (118 mils) (6)

Oval holes:

- 0.6x1.4 mm (24x55 mils) (2)
- 0.6x1.7 mm (24x67 mils) (2)

Drill tools (including vias and computing adjusts and rounding):

- 0.5 mm (20 mils) (71)
- 0.65 mm (26 mils) (2)
- 0.7 mm (28 mils) (4)
- 3.0 mm (118 mils) (6)




