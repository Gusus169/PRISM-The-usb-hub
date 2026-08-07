# 'PRISM' The USB Hub V2.0



### A compact 4-port USB 2.0 hub PCB featuring ESD protection,  PTC resettable fuses, and per-port LED indicators; All packed in a small keychain design form.

[Key Features](#key-features) • [PCB](#pcb) • [BOM](#bom) • [License](#license)


![Banner1](assets/Render5.png)



## About

PRISM is a USB Type-C-based input USB hub that splits it into four downstream ports — just like a prism splits light. Built from scratch starting in EasyEDA Pro(V1), later moving to KiCad and finishing off with Blender animated renders, this project pushed me deep into reading datasheets, understanding circuit protection, and the difference between making something work and engineering something worth making.


## Key Features

- Main IC - SL2.1S (IC)
- Static Circuit Protection - ESD diodes on all ports
- Short-Circuit protection - PTC on all downstream ports
- Downstream port features - 2x USB-Type-C
                           - 2x USB-Type-A
- Upstream port - USB-Type-C
- Multi-Layer capacitor decoupling
- Compact 2-layer PCB, designed to be a keychain at ~3" × 1.2".

## PCB

Designed in EasyEDA Pro(V1), Further Refined in KiCad(V2).

### Schematic

![Schematic](assets/schematic.png)

### PCB

**Front:**

![PCB Front](assets/pcb_front.png)

**Back:**

![PCB Back](assets/pcb_back.png)


### KiCad Renders 

**Front:**

![PCB Front](assets/pcb_front3d.png)

**Back:**

![PCB Back](assets/pcb_back3d.png)



## BOM

|Index|	LCSC#	| Product Name|	Manufacturer|Package|	Design Refrence#|	Quantity|	Product Link|
|-----|-------|-------------|--------------|------|-----------------|---------|-------------|
|1	|C207022|	0805L050WR|	Littelfuse|	805|	F1,F2,F3,F4|	4|	https://www.lcsc.com/product-detail/C207022.html|
|2	|C668591|	10.0 QHHTZB6.3|	SHOU HAN|	SMD|	USB1,USB2	|2	|https://www.lcsc.com/product-detail/C668591.html|
|3	|C1591|	CL10B104KB8NNNC|	Samsung Electro-Mechanics|	603	|C1-8,C11-17|	15|https://www.lcsc.com/product-detail/C1591.html|
|4	|C2906982|	FRC0603F1002TS|	FOJAN|	603|	R1,R10,R2,R3,R4,R5,R6,R7,R8,R9|	10	|https://www.lcsc.com/product-detail/C2906982.html|
|5	|C2907035|	FRC0603F4R70TS|	FOJAN|	603|	R11|	1	|https://www.lcsc.com/product-detail/C2907035.html|
|6	|C2684433|	SL2.1s	|CoreChips|	SSOP-16|	U1|	1	|https://www.lcsc.com/product-detail/C2684433.html|
|7	|C2765186|TYPE-C 16PIN 2MD(073)|	SHOU HAN|	SMD	|USB0,USB3,USB4	|1	|https://www.lcsc.com/product-detail/C2765186.html|
|8	|C7519|	USBLC6-2SC6|	ST|	SOT-23-6L|	D0,D1,D2,D3,D4 |3	|https://www.lcsc.com/product-detail/C7519.html|
|9	|C965799|	XL-1608SURC-06|	XINGLIGHT	|603	|LED1,LED2,LED3,LED4|	5	|https://www.lcsc.com/product-detail/C965799.html|
|10|	C22367835|	HGC1206R5476M250NSPJ|	Chinocera|	1206|	C9|	4	|https://www.lcsc.com/product-detail/C22367835.html|




## What I Learned

- How to read the reference schematic provided by the manufacturer
- In-depth functionality of capacitors - Why they are used in pairs
- Functionality of ESD & PTC
- Difference in USB types and their speeds
- Differential pair routing and its importance

## Credits

This project uses:

- [EasyEDA Pro](https://pro.easyeda.com/) 
- [KiCad](https://www.kicad.org/download/)
- [JLCPCB](https://jlcpcb.com/) for PCB fabrication
- [LCSC](https://www.lcsc.com/) for component sourcing
- Based on the [Hack Club USB Hub guide](https://macondo.hackclub.com/docs/usb-hub)


## License

MIT
