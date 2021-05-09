# Axon

![Built Axon](img/axon_built.jpg)
*Axon version 1.0 built with Durock T1 and GMK Bento*

Axon is a 40% custom mechanical keyboard with through-hole components, inspired by other keyboards such as [gingham](https://github.com/yiancar/gingham_pcb) and [plaid](https://github.com/hsgw/plaid). Axon runs on an ATmega328P using VUSB and QMK.

Notable features include an [HHKB-style](https://happyhackingkb.com/) layout with missing lower corners, and a split spacebar. I never use my right thumb to hit spacebar, so the split allows me to use my right thumb to access additional keyboard layers. A full write-up can be found [on my website](https://www.robinliu.me/axon).

### Images

**Layout:**

![Layout](img/axon_layer_base.png)

**PCB EDA Screenshot:**

![PCB EDA Screenshot](img/axon_pcb_eda.png)

### Component Libraries

**Symbols:**
- [Keyboard symbols by Hasu](https://github.com/tmk/kicad_lib_tmk)

**Footprints:**
- [Keyswitches by Daprice](https://github.com/daprice/keyswitches.pretty)
- My own footprints for silkscreen art. Can be found in `lib/`

### Versions
**1.0:**
- Initial release, production version for personal use.

**1.1:**
- Spacebar widths can be swapped (i.e. 2.25u-2.75u instead of 2.75u-2.25u)
- Update screw placements to ensure acrylic cover symmetry along both x and y axis
- Fixed issues with stabilizer interference.
- Optimize decoupling capacitor placement.
- Polyfuse now has room to lay horizontally if desired.
- Back side silkscreen accurately reflects default layout.
- Numerous minor layout and routing changes.
- Added version number to rear silkscreen
- Updated license.

## License
 
Axon version 1.1 and higher is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/)
If you have built upon this project and have significantly altered the design, the non-commercial clause can be waived.
