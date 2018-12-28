# WarthoggitClone
Clone of the Warthoggit Joystick PCB

## 2-Layer
* Octopart BOM: https://octopart.com/bom-tool/HYrWh7Pe
* OSHPark PCB: https://oshpark.com/shared_projects/x2CpRCvp
* Gerblook: http://gerblook.org/pcb/NEAhkPDx7kaQgrBpLWPrQZ

## 4-Layer
* Octopart BOM: https://octopart.com/bom-tool/o3ovRzzJ
* OSHPark PCB: https://oshpark.com/shared_projects/Q2SqhzfM
* Gerblook: http://gerblook.org/pcb/AL6aAQwq3UeULmAeNpxRJG

----

## Original Reddit Post:
https://www.reddit.com/r/hoggit/comments/46pdjy/warthoggit_pcb_series_the_circuitboard_for_your/

Thanks to /u/sniporbob, /u/sostroch, and /u/brocollocalypse from the Warthog circuitry post, we now understand how the electronics in the grip of the Warthog work. The info was taken and used to design this new series of PCB. I present to you 3 versions:

* [Warthoggit Min](https://rbfi.io/dl.php?key=/xgUP/tmp_10092-WarthoggitMin904008334.zip)

* [Warthoggit Mid](https://rbfi.io/dl.php?key=/YsRy/tmp_10092-WarthoggitMid430238092.zip)

* [Warthoggit Max](https://rbfi.io/dl.php?key=/8pkO/tmp_10092-WarthoggitMax1664382632.zip)

The appropriate board to use depends on the complexity of the grip.

Min offers 7 buttons, but is the smallest of the three.

Mid offers 11 buttons and an 8 way hat.

Max offers the full 19 buttons and an 8 way hat.

Included in each zip file are PDF masks, SVG masks, Extended Gerber files, and the source file to edit the designs in Fritzing. Also included is a text file listing the dimensions of the board, and a drawing showing which pin on the circuitboard connects to which pin on the PS/2 connector on the Warthog joystick base.

The circuit components are as follows:

* All resistors = 100k ohm, package 0603

* All capacitors = 0.1uf, package 0603

* All ICs = HEF4021BT

* All connectors = Picoblade 53047 series, or any connector of your choice with a 1.25mm pin spacing.

Minimum trace width is 12 mils, please make sure your PCB manufacturer supports this (they should).

The boards do not have predrilled mounting holes in the design so you can insert your own of the correct size. There is space for 2 holes on the max and 1 hole on the others. You can let the board free hang inside the grip or use a dab of hot glue if you don't care about mounting holes.

Finally, this design is untested! I just finished it and haven't had a chance to get one built or tested. It may take me a few weeks. I spent several hours quadruple checking everything so I'm quite confident it will work.

License: GPLv3 because I don't know what's best. If a different license would be better please let me know.
