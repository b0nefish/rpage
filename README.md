![](docs/img/rpage_logo.png)
## Resistance's Portable-Adventure-Game-Engine

[![Build Status](https://travis-ci.org/ResistanceVault/rpage.svg?branch=master)](https://travis-ci.org/ResistanceVault/rpage)

**R-PAGE** (pronounced 'arpège') is a **C framework** meant to accelerate the creation of **adventure games** for the Amiga OCS/ECS range of computers. It is designed with portability in mind, speed performance being a lesser concern.<br>
R-PAGE is brought to you by the **demoscene** group [RESISTANCE](https://resistance.no/).

* Written in C language
* AmigaOS & OS-friendly for all the access to the Amiga hardware
* Portable code, builds on SAS/C
* ~~Reportedly works on MorphOS using the built-in AmigaOS emulation layer~~
* AMIGA OCS/ECS only (AGA is on the roadmap)

### What can I do with this ?
At the moment, R-PAGE is more a framework than a full feature engine. Feel free to use it as a boostrap for your own adventure project. The roadmap, however, includes a very basic adventure game to showcase the features of this framework.

### Where is the API ?
You should start looking for [frwk.h](rpage/frwk.h)

### Actual games based on R-PAGE:
* Athanor 2 by www.safargames.fr
* ShuffleP\*ck adventures (work in progress title)
* Next adventure game by www.safargames.fr

### 3rd party softwares included in R-PAGE:
* [tinfl.c](https://github.com/richgel999/miniz) (Zlib compression/decompression) by Richard Geldreich
* [Shrinkler](https://github.com/askeksa/Shrinkler) 68k ASM decompression routine by Aske Simon Christensen
* [nrv2s](https://github.com/jonathanbennett73/amiga-pjz-sax-offender/tree/master/Projects/SaxOffender/Framework/Depack) 68k ASM decompression routine by Ross
* [ptreplay.library](http://aminet.net/package/mus/play/ptreplay66) ProTracker replay library by Mattias Karlsson and Andreas
Palsson
* [FP_ADPCM](http://aminet.net/package/util/pack/MT_ADPCM) ADPCM codec by Tobias "MastaTabs" Seiler & Christian "FlowerPower" Buchner.

## License/Contact
R-PAGE is released under the MIT License. See [license.txt](license.txt).<br>
Reach us on Twitter [@RESISTANCE_NO](https://twitter.com/RESISTANCE_NO) or WWW [RESISTANCE HQ](https://resistance.no/)


## Sample screenshots

![Screenshot](.screenshots/athanor2_shot0.png)
![Screenshot](.screenshots/athanor2_shot1.png)
![Screenshot](.screenshots/athanor2_shot2.png)
