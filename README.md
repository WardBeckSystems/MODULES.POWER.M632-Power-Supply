# M632 Power Supply · Power

Ward-Beck Systems M632, 1983|16. Wiki page: [M632 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M632.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 27 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 56 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 12 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [4 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [19xx - M632 - P002 - 1-1.jpg](MANUALS/19xx%20-%20M632%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Output voltage** | +25 volts dc at load amperes currents from |
| **Line regulation** | 25% for Line variations from 105 ac 125 volts |
| **Load regulation** | 0.1% for load variations from zero full load. |
| **Ripple and noise** | Less than 500 microvolts RMS for all Line and load conditions specified above |
| **Internal impedance** | Less than 0.05 ohm from |
| **Stability** | volt measured over an minutes warmup. hour period, after |
| **Protection** | Overcurrent and short circuit foldback. Overvoltage crowbar. Unregulated Output |
| **Output voltage** | +32 volts dc +/-10% nominal Load currents from amperes, 115 volts ac input. |
| **Ripple** | Less than volt RMS load. |
| **Ac input** | 125 volts ac, 60 Hz, 100 VA maximum. |
| **Ambient temperature** | degrees Celsius. Dimensions: wide 3.4&quot; high 13.7&quot; deep (130 mm Mm 348 mm) |
| **Weight** | 8.8 Ib. |

## Circuit description

From [19xx - M632 - P003 - 2-1.jpg](MANUALS/19xx%20-%20M632%20-%20P003%20-%202-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M632 power supply used primarily the M703B and M712B intercom modules intercom systems utilizing The primary winding the power transformer Tio1 operation from 115 volt ac, 60 Hz Line. designed for Bridge rectifier CR1OI and filter capacitor C101 follow the secondary transformer winding. The unregulated dc output brought out P2, pins after passing through fuse F102. second path originating the rectifier output fed via fuse F103 Pass transistor 0101 and resistor R101 the regulated output at P2, pins 7 &amp; The LED &quot;power on indicator DS101 connected across the regulated output voltage. The primary voltage regulator circuit as weli as the overvoltage crowbar protection circuit are contained on the 9-104 regulator card_ u1 the basic integrated circuit regulator which contains the required referencing voltage and amplifiers The internal reference voltage compared with portion the 25 volt regulated output via voltage divider RB, R9 and R10. resultant error voltage pin u1 driving the current booster transistor 01 _ The appears collector output drives the main external series pass transistor 0101. remote sensing the 25 volt load voltage required cut jumper and connect P2 Pin with separate sense wire the load directly. u1 contains internal current limiting and foldback circuits. The voltage drop developed across Rioi fed U1 pin via voltage divider RL/R5. When the supply current reaches approximately 3.7 amperes, foldback current Limiting sets in. With the supply output shorted, the current limited 0.5 amperes maximum Overvoltage protection provided by crowbar' SCR 02. The sensing network consists CR3, C6, RII and R12. Should the output voltage rise approximately 27 volts due breakdown any the regulator components 02 wili fire and thus short-circuit the power supply resulting the blowing fuse F103

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1qwaXPFTcMtEARXsJTFEtihuwmjS1Mqwh/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1qwaXPFTcMtEARXsJTFEtihuwmjS1Mqwh" width="240" alt="1994 - M632 - DOC - 94033-01-001 - FUNCIIONAL DIAGRAM IXPICAL NNTERCQM CONTROL SCHEMAIC SSUEI REMSION.jpg"></a><br><sub>1994|27 · DOC - 94033-01-001 - FUNCIIONAL DIAGRAM IXPICAL NNTERCQM CONTROL SCHEMAIC SSUEI REMSION · <a href="SCHEMATICS/1994%20-%20M632%20-%20DOC%20-%2094033-01-001%20-%20FUNCIIONAL%20DIAGRAM%20IXPICAL%20NNTERCQM%20CONTROL%20SCHEMAIC%20SSUEI%20REMSION%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmY5Q1NjcElFOW8/view?resourcekey=0-foLVIlrVnsTUox4Wf2NJwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmY5Q1NjcElFOW8&resourcekey=0-foLVIlrVnsTUox4Wf2NJwQ" width="240" alt="19xx - M632 - 632-02-001 - OVIDJ POWER SUPFLY.jpg"></a><br><sub>19xx - M632 - 632-02-001 - OVIDJ POWER SUPFLY · <a href="SCHEMATICS/19xx%20-%20M632%20-%20632-02-001%20-%20OVIDJ%20POWER%20SUPFLY%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblZYLXNNbHV4RjQ/view?resourcekey=0-Ui4Yt_UI4Jq6Gp1StQJXtw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblZYLXNNbHV4RjQ&resourcekey=0-Ui4Yt_UI4Jq6Gp1StQJXtw" width="240" alt="19xx - M632 - 632-06-001 - REGULATOR BOARD.jpg"></a><br><sub>19xx - M632 - 632-06-001 - REGULATOR BOARD · <a href="SCHEMATICS/19xx%20-%20M632%20-%20632-06-001%20-%20REGULATOR%20BOARD%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1uFHftuCx8dPueVrxPV7ulLp3uiDCd-IO/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1uFHftuCx8dPueVrxPV7ulLp3uiDCd-IO" width="240" alt="19xx - M632 - DOC - 712-02-104 - TEST FIXTURE SCHEMATIC NOTE BINDING PEST TERMINALS USED.jpg"></a><br><sub>19xx - M632 - DOC - 712-02-104 - TEST FIXTURE SCHEMATIC NOTE BINDING PEST TERMINALS USED · <a href="SCHEMATICS/19xx%20-%20M632%20-%20DOC%20-%20712-02-104%20-%20TEST%20FIXTURE%20SCHEMATIC%20NOTE%20BINDING%20PEST%20TERMINALS%20USED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1983 - 632-06-002 - POWER SUPPLY COMPONENT LAYOUT - DRN P. Mahoney - ENG MRW - ISS 2.jpg`

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNlZlOW5yeGR3RTQ/view?resourcekey=0-v3Vz_p-PD4jebaeDg97-TA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNlZlOW5yeGR3RTQ&resourcekey=0-v3Vz_p-PD4jebaeDg97-TA" width="240" alt="19xx - M632 - P001 - Title Page.jpg"></a><br><sub>19xx - M632 - P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUkpVUEJFZWhySkE/view?resourcekey=0-uBgoUNCfbCBjq-cOWW770g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUkpVUEJFZWhySkE&resourcekey=0-uBgoUNCfbCBjq-cOWW770g" width="240" alt="19xx - M632 - P002 - 1-1.jpg"></a><br><sub>19xx - M632 - P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT1VGWXNPbHpvUGM/view?resourcekey=0-JfH3Wxf6yJQlJ1J_D2g0PQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT1VGWXNPbHpvUGM&resourcekey=0-JfH3Wxf6yJQlJ1J_D2g0PQ" width="240" alt="19xx - M632 - P003 - 2-1.jpg"></a><br><sub>19xx - M632 - P003 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2oyRFdqQVZjSkU/view?resourcekey=0-7uHUqG5lhHU_2AP9iBn3pg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2oyRFdqQVZjSkU&resourcekey=0-7uHUqG5lhHU_2AP9iBn3pg" width="240" alt="19xx - M632 - P004 - 3-1.jpg"></a><br><sub>19xx - M632 - P004 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVNnZ2xTSlV4Y0U/view?resourcekey=0--sM60uxM3podx3Usj-9WCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVNnZ2xTSlV4Y0U&resourcekey=0--sM60uxM3podx3Usj-9WCA" width="240" alt="19xx - M632 - P005 - 3-2.jpg"></a><br><sub>19xx - M632 - P005 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNE42VWZSR0Q0ek0/view?resourcekey=0-poIeNNyFw25GHnM9lf1fIw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNE42VWZSR0Q0ek0&resourcekey=0-poIeNNyFw25GHnM9lf1fIw" width="240" alt="19xx - M632 - Power Supply (2).pdf"></a><br><sub>19xx - M632 - Power Supply (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1BxUGxYUVBjODg/view?resourcekey=0-dsyYkGYSQDSxJb8L9ishYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1BxUGxYUVBjODg&resourcekey=0-dsyYkGYSQDSxJb8L9ishYw" width="240" alt="19xx - M632 - Power Supply.pdf"></a><br><sub>19xx - M632 - Power Supply</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1994 - M632 - DOC - 94033-01-001 - FUNCIIONAL DIAGRAM IXPICAL NNTERCQM CONTROL SCHEMAIC SSUEI REMSION.kicad_sch](KICAD/1994%20-%20M632%20-%20DOC%20-%2094033-01-001%20-%20FUNCIIONAL%20DIAGRAM%20IXPICAL%20NNTERCQM%20CONTROL%20SCHEMAIC%20SSUEI%20REMSION.kicad_sch)
- [19xx - M632 - DOC - 712-02-104 - TEST FIXTURE SCHEMATIC NOTE BINDING PEST TERMINALS USED.kicad_sch](KICAD/19xx%20-%20M632%20-%20DOC%20-%20712-02-104%20-%20TEST%20FIXTURE%20SCHEMATIC%20NOTE%20BINDING%20PEST%20TERMINALS%20USED.kicad_sch)
- [19xx - M632 - Power Supply (2) p6.kicad_sch](KICAD/19xx%20-%20M632%20-%20Power%20Supply%20(2)%20p6.kicad_sch)
- [M632.kicad_sym](KICAD/M632.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
