<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

My project has switches 1 and 2 connected to an and gate, and switch 7 is connected to a not gate. The output of the and gate goes to out1 and the output of the not gate goes to out6

## How to test

for the inverter (switch 7) 
|  input   |  output  |
|----------|----------|
| 00000000 | xxxxxxx1 |
| 00000001 | xxxxxxx0 |

and for the and gate 
|  input   |  output  |
|----------|----------|
| 00000010 | xxxxxx00 |
| 00000011 | xxxxxx01 |
| 00000000 | xxxxxx00 |
| 00000001 | xxxxxx00 |

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
