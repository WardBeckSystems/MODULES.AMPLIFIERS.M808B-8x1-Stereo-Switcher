# M808B 8x1 Stereo Switcher · Amplifiers

Ward-Beck Systems M808B, 1994|27. Wiki page: [M808B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M808B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 5 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 8 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 3 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 2 |

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQnhJVEpwX1J2VWc/view?resourcekey=0-T2jd6y0dOxAaSm1CVczSyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQnhJVEpwX1J2VWc&resourcekey=0-T2jd6y0dOxAaSm1CVczSyw" width="240" alt="1994 - M808B - 808-02-003 - MODULE SCHEMA TIC.jpg"></a><br><sub>1994|27 · 808-02-003 - MODULE SCHEMA TIC · <a href="SCHEMATICS/1994%20-%20M808B%20-%20808-02-003%20-%20MODULE%20SCHEMA%20TIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ25nNXAzUWxsN0E/view?resourcekey=0-639q6YqpVcwHStPfcpucGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ25nNXAzUWxsN0E&resourcekey=0-639q6YqpVcwHStPfcpucGw" width="240" alt="1994 - M808B - CONNECTOR LAYOUT.jpg"></a><br><sub>1994|27 · CONNECTOR LAYOUT · <a href="PINOUTS/1994%20-%20M808B%20-%20CONNECTOR%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-1 | LEFT IN 8 | in | INPUT 8 L | high |
| P1-2 | RIGHT IN 8 | in | INPUT 8 R | high |
| P1-3 | LEFT IN 7 | in | INPUT 7 L | high |
| P1-4 | RIGHT IN 7 | in | INPUT 7 R | high |
| P1-5 | LEFT IN 6 | in | INPUT 6 L | high |
| P1-6 | RIGHT IN 6 | in | INPUT 6 R | high |
| P1-7 | LEFT IN 5 | in | INPUT 5 L | high |
| P1-8 | RIGHT IN 5 | in | INPUT 5 R | high |
| P1-9 | LEFT IN 4 | in | INPUT 4 L | high |
| P1-10 | RIGHT IN 4 | in | INPUT 4 R | high |
| P1-11 | LEFT IN 3 | in | INPUT 3 L | high |
| P1-12 | RIGHT IN 3 | in | INPUT 3 R | high |
| P1-13 | LEFT IN 2 | in | INPUT 2 L | high |
| P1-14 | RIGHT IN 2 | in | INPUT 2 R | high |
| P1-15 | LEFT IN 1 | in | INPUT 1 L | high |
| P1-16 | RIGHT IN 1 | in | INPUT 1 R | high |
| P1-17 | SHIELD GROUND | shield | shield | high |
| P1-18 | CHASSIS | ground |  | high |
| P1-19 | N/C | nc |  | high |
| P1-20 | N/C | nc |  | high |
| P1-21 | LEFT OUT | out | OUTPUT L | high |
| P1-22 | RIGHT OUT | out | OUTPUT R | high |
| P1-A | LEFT IN 8 | in | INPUT 8 L | high |
| P1-B | RIGHT IN 8 | in | INPUT 8 R | high |
| P1-C | LEFT IN 7 | in | INPUT 7 L | high |
| P1-D | RIGHT IN 7 | in | INPUT 7 R | high |
| P1-E | LEFT IN 6 | in | INPUT 6 L | high |
| P1-F | RIGHT IN 6 | in | INPUT 6 R | high |
| P1-H | LEFT IN 5 | in | INPUT 5 L | high |
| P1-J | RIGHT IN 5 | in | INPUT 5 R | high |
| P1-K | LEFT IN 4 | in | INPUT 4 L | high |
| P1-L | RIGHT IN 4 | in | INPUT 4 R | high |
| P1-M | LEFT IN 3 | in | INPUT 3 L | high |
| P1-N | RIGHT IN 3 | in | INPUT 3 R | high |
| P1-P | LEFT IN 2 | in | INPUT 2 L | high |
| P1-R | RIGHT IN 2 | in | INPUT 2 R | high |
| P1-S | LEFT IN 1 | in | INPUT 1 L | high |
| P1-T | RIGHT IN 1 | in | INPUT 1 R | high |
| P1-U | N/C | nc |  | high |
| P1-V | CHASSIS | ground |  | high |
| P1-W | N/C | nc |  | high |
| P1-X | N/C | nc |  | high |
| P1-Y | LEFT OUT | out | OUTPUT L | high |
| P1-Z | RIGHT OUT | out | OUTPUT R | high |
| P2-10 | CONTROL 1 | control_in | CTL 1 | high |
| P2-11 | CONTROL 3 | control_in | CTL 3 | high |
| P2-14 | CONTROL 5 | control_in | CTL 5 | high |
| P2-15 | CONTROL 6 | control_in | CTL 6 | high |
| P2-16 | CONTROL 8 | control_in | CTL 8 | high |
| P2-21 | +25 V | power |  | high |
| P2-22 | CONTROL COMMON | ground |  | high |
| P2-L | CONTROL 2 | control_in | CTL 2 | high |
| P2-M | CONTROL 4 | control_in | CTL 4 | high |
| P2-R | CONTROL 5 | control_in | CTL 5 | high |
| P2-S | CONTROL 7 | control_in | CTL 7 | high |
| P2-T | CANCEL | control_in | CANCEL | high |
| P2-Y | +25 V | power |  | high |
| P2-Z | CHASSIS GROUND | ground |  | high |

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1994 - M808B - 808-02-003 - MODULE SCHEMA TIC.kicad_sch](KICAD/1994%20-%20M808B%20-%20808-02-003%20-%20MODULE%20SCHEMA%20TIC.kicad_sch)
- [M808B.kicad_sym](KICAD/M808B.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
