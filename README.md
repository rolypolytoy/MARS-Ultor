UHV for <$1000.

## Turbomolecular Pump

We of course buy a [rotary vane pump](https://www.amazon.in/HAVC-RX-1S-Single-Stage-Vacuum/dp/B079J3Y781) for the roughing stage.

[Two fully ceramic ball bearings](https://www.amazon.in/12x28x8mm-Precision-Equipment-Installation-Maintenance/dp/B0C1JSDWKB) (12ID, 28OD, 8H) can be bought for a pittance so we don't need to do maintenance or lubrication to get to the >40k RPM we need, nor do we need to fiddle around with any messy magnetics. We're using a [Brushless DC Motor](https://robu.in/product/t-motors-2207-v2-1750-kv-brushless-motor/) for the >40k RPM speeds (at up to 800W), an [electronic speed controller](https://robu.in/product/readytosky-80a-esc-2-6s-brushless-esc-speed-controller-for-rc-drone//), a [24VDC 40A Power Supply](https://www.amazon.in/Switching-Industrial-Transformer-Converter-Security/dp/B0BR87VXHJ), and a basic touchscreen [LCD Screen Display](https://www.amazon.in/Robocraze-Colour-Screen-320x480-Arduino/dp/B07922JJYM) for IO with good UI/UX. Raspberry Pi 5 will of course be its MCU.

Add teeny hole for positioning.

No welding for rotor/stator assembly- simply use spacing rings for the shaft/outside for rotor/stator respectively

DN250 CF/ CF 10" inlet. KF 40 outlet.

Cooling via [2 Arctic P12 MAX fans](https://www.amazon.in/ARCTIC-P12-Max-Performance-Regulation/dp/B09VDNKL4G?).

O-rings etc.

Note: spacers made with Al-3003-O and heated after application to fill micro-imperfections. Sheet metal is Al-6061-T4 (heat treated after for aging to full strength)

Tool and die for turbomol sheet metal (Al-7075 1 mm w/anodization and heat treatment):

Material cost:
P20 plate 250 x 250 x 20 mm  → 10 kg @ ₹120/kg  → ₹1,200
1045 plate 300 x 300 x 20 mm (top) → 14 kg @ ₹80/kg  → ₹1,120
1045 plate 300 x 300 x 20 mm (bottom) → 14 kg @ ₹80/kg  → ₹1,120
1045 plate 300 x 300 x 12 mm (stripper) → 8.5 kg @ ₹80/kg → ₹680
Total steel ≈ ₹4,120 

Machining cost:
P20 die block    250×250×20 mm  3.5 h VMC + 1.5 h EDM  → ₹ 6,450
1045 top shoe    300×300×20 mm  1.0 h VMC               → ₹ 1,000
1045 bottom shoe 300×300×20 mm  1.0 h VMC               → ₹ 1,000
1045 stripper    300×300×12 mm  0.8 h VMC               → ₹ 800

Total machining ≈ ₹ 9,250

Total cost = 4 * (4120 + 9250) = ₹ 53,480 (fixed)

## Ion Pump

We're using a getter (sputtering) ion pump design. For this, we will of course need a [high voltage power supply](https://ar.aliexpress.com/item/1005003518403820.html) which will be connected (+5kV) to the anode, and GND to the cathode. The cathode must be made from titanium, the anodes from aluminium, and an axial magnetic field provided by two [huge permanent Neodymium magnets](https://www.amazon.in/Neodymium-Diameter-Magnetics-Underwater-Retrieval/dp/B07Q6V25NL) with 120.7 mm diameter and 17.8 mm height.

We'll be using the patented [StarCell design](https://patents.google.com/patent/US6388385B1/en) that Agilent HAD (past tense). It expired in 2020, and regardless, the patent was never filed in India, so we're good to use it. Maybe not for the first few models, but it allows, apart from the technical benefits of the design, the creation of anodes by bending sheet metal, which is a tremendous cost-saver in the even reasonably middle-term. Hehehe.

## Bayard-Alpert Gauge

Collector: 0.1 mm OD, Cathode/Anode: 0.25 mm OD tungsten wire. 
