# WarthoggitClone
Clone of the Warthoggit Joystick PCB

### 2-Layer
* Octopart BOM: https://octopart.com/bom-tool/HYrWh7Pe
* OSHPark PCB: https://oshpark.com/shared_projects/x2CpRCvp
* Gerblook: http://gerblook.org/pcb/NEAhkPDx7kaQgrBpLWPrQZ

### 4-Layer
* Octopart BOM: https://octopart.com/bom-tool/o3ovRzzJ
* OSHPark PCB: https://oshpark.com/shared_projects/Q2SqhzfM
* Gerblook: http://gerblook.org/pcb/AL6aAQwq3UeULmAeNpxRJG

---
## Info

Uses three cascaded 8-bit parallel-to-serial shift registers, with the final downstream output hooked to an SPI MISO line.  The whole stack is clocked by the SPI CLK and latched by SPI CS.  This variant uses automotive qualified parts to withstand the vibrations expected in a joystick.

* STM HCF4021
* Panasonic 0805 package 10k ohm resistors (can be replaced with 100k if debouncing is an issue)
* 100nF 0805 capacitors, ceramic, X7R

---

## Original Reddit Post:
https://www.reddit.com/r/hoggit/comments/46pdjy/warthoggit_pcb_series_the_circuitboard_for_your/
