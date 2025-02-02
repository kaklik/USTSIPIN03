# PCB

Board size: 70.61x50.29 mm (2.78x1.98 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: HAL SnPb
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
| F.Mask               | Top Solder Mask      |                  |        10 |                 |           |              |
| F.Cu                 | copper               |                  |        35 |                 |           |              |
| dielectric 1         | core                 |                  |      1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |        35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   |                  |        10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |           |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |           |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.2 mm (8 mils)

- By design rules: 0.2 mm (8 mils)

Drill: 0.5 mm (20 mils)

- Vias: 0.5 mm (20 mils) [Design: 0.4 mm (16 mils)]
- Pads: 0.85 mm (33 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.8/0.4 mm (31/16 mils)

- By design rules: 0.8/0.3 mm (31/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 59 (thru: 59 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.15 mm (6 mils)

- By design rules: 0.26 mm (10 mils)

Eurocircuits class: 4B
- Using min drill 0.5 mm for an OAR of 0.15 mm


# General stats

Components count: (SMD/THT)

- Top: 0/6 (THT)
- Bottom: 96/1 (SMD + THT)

Defined tracks:

- 0.2 mm (8 mils)
- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)
- 0.6 mm (24 mils)
- 0.7 mm (28 mils)
- 0.8 mm (31 mils)

Used tracks:

- 0.2 mm (8 mils) (2) defined: yes
- 0.3 mm (12 mils) (136) defined: yes
- 0.4 mm (16 mils) (75) defined: yes
- 0.45 mm (18 mils) (443) defined: no
- 0.5 mm (20 mils) (4) defined: yes
- 0.6 mm (24 mils) (24) defined: yes
- 0.7 mm (28 mils) (30) defined: yes

Defined vias:


Used vias:

- 0.8/0.4 mm (31/16 mils) (Count: 59, Aspect: 2.0 A) defined: no

Holes (excluding vias):

- 0.76 mm (30 mils) (2)
- 0.89 mm (35 mils) (30)
- 3.0 mm (118 mils) (4)

Oval holes:


Drill tools (including vias and computing adjusts and rounding):

- 0.5 mm (20 mils) (59)
- 0.85 mm (33 mils) (2)
- 1.0 mm (39 mils) (30)
- 3.1 mm (122 mils) (4)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Total  |             281 |     379.06 |      1.89 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



