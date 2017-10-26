# AD8307 RF Wattmeter

I always wanted to build a RF Wattmeter with the AD8307 and OZ2CPU design. I was looking for PIC MCUs and found that PIC16F876 is going to NRND, so after this I found it was the best time to start this project. It's a AD8307 RF Wattmeter from OZ2CPU in a PCB that can be placed on a Hammond 1590B box.

### Bare PCB
![Preview](https://github.com/PY1CX/AD8307-RF-Wattmeter/blob/master/BarePCB.png?raw=true)

### Prototype Working
![Preview](https://github.com/PY1CX/AD8307-RF-Wattmeter/raw/master/Prototype-Working.png)

ATTENTION KNOW BUGS:

For V1.0 boards:
- The PCB project suffer from a pin swap on MC78L05. Pin 1 and Pin 3 are swapped, you MUST correct it on your building or your PIC will die from overvoltage.
- I put a place for a 16x2 LCD but the correct one is a 20x4!


Original Schematic and Software: http://www.webx.dk/oz2cpu/radios/miliwatt.htm
