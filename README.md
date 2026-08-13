[![A.C. Wright](https://raw.githubusercontent.com/acwright/acwright/master/banner.png "A.C. Wright")](https://www.youtube.com/@acwrightdesign)

# A.C. Wright

I build 8-bit computers, and I'm making a video series about programming them.

Software developer and maker in Lincoln, Nebraska. Most of what is here is the AC6502
project — a family of homebrew 6502 machines, their firmware, their emulators, and the
tools that go with them.

📺 **[youtube.com/@acwrightdesign](https://www.youtube.com/@acwrightdesign)** &nbsp;·&nbsp;
🎮 **[acwrightdesign.itch.io](https://acwrightdesign.itch.io)** &nbsp;·&nbsp;
✉️ **[acwrightdesign@gmail.com](mailto:acwrightdesign@gmail.com)**

## 6502 Assembly — an upcoming video series

A course in 6502 assembly language, taught one machine at a time.

**In production — the first episode isn't out yet.** The playlist is where episodes land
as they go up, and everything being built for them is already public below.

It starts on a bare-bones single-board computer with eight LEDs and no display at all,
where there is nothing sitting between you and the processor. Twenty episodes on the
fundamentals — registers, memory, addressing modes, the instruction set, interrupts,
cycles and timing — ending by building the game "Kill the Bit" on those eight LEDs.

From there I hope to climb through the machines that defined the 8-bit era: the Apple 1,
the PET, the VIC-20, the Commodore 64, the Atari 800, the Apple II, the NES, the Atari
2600 and beyond. One new idea per machine.

You won't need any hardware to follow along — everything runs in an emulator in your
browser.

| | |
|---|---|
| ▶️ [Series 01 — The AC6502 KIM](https://www.youtube.com/playlist?list=PLeNsHLLppL50) | The playlist, as episodes go up |
| 📂 [6502-ASSEMBLY](https://github.com/acwright/6502-ASSEMBLY) | Scripts, slides, type-in cards and every example program |
| 🕹️ [KIMULATOR](https://acwright.github.io/6502-KIMULATOR/) | Run the programs in your browser — no install, no account |
| 📖 [6502-DOCS](https://acwright.github.io/6502-DOCS/) | The user's and programmer's guide for the AC6502 family |

## The Machines

Homebrew 6502 computers. All open source — schematics, gerbers and firmware — so build
one if you want one.

| | |
|---|---|
| [6502-ACE](https://github.com/acwright/6502-ACE) | **A**ll-in-one **C**omputer **E**xperience — the whole family on a single board: 65C02, VGA video, SID audio, storage, serial, GPIO and a real-time clock |
| [6502-KIM](https://github.com/acwright/6502-KIM) | **K**eypad **I**nput **M**onitor — a 65C02, a 24-key pad, a 16×2 LCD and eight LEDs. Boots into a hex monitor. The machine series 01 is taught on |
| [6502-DEV](https://github.com/acwright/6502-DEV) | **D**evelopment **E**nvironment **V**ehicle — a Teensy 4.1 stands in for the CPU, with run/stop, single-step and a clock you can slow to a crawl |
| [6502-COB](https://github.com/acwright/6502-COB) | **C**omputer **o**n a **B**ackplane — the modular desktop: card slots, up to 544KB of RAM, and a card for every peripheral |
| [6502-VCS](https://github.com/acwright/6502-VCS) | **V**ideo **C**omputer **S**ystem — the console of the family: ROM cartridges, VGA out, SID sound and 2600-compatible joysticks |
| [APL1](https://github.com/acwright/APL1) | A homebrew Apple 1 replica — 6502, 65C21 PIA and WozMon, with a microcontroller terminal adding PS/2 and serial |

## Firmware, Emulators & Tools

| | |
|---|---|
| [6502-BIOS](https://github.com/acwright/6502-BIOS) | The 32KB ROM every machine boots: the Kernal, the Monitor and BASIC. It probes the I/O slots, so missing cards are simply skipped |
| [6502-EMULATOR](https://github.com/acwright/6502-EMULATOR) | The family, emulated — cycle-accurate 65C02, TMS9918 video, SID audio. Browser or desktop |
| [6502-KIMULATOR](https://github.com/acwright/6502-KIMULATOR) | The KIM in particular — pad, LCD and the eight LEDs on the bus. Browser or desktop |
| [6502-PICOCALC](https://github.com/acwright/6502-PICOCALC) | The whole machine as one `.uf2` for the ClockworkPi PicoCalc — a handheld AC6502 |
| [6502-ASM](https://github.com/acwright/6502-ASM) | Assembly programs beyond the ones in the series, each with a Makefile |
| [6502-PRG](https://github.com/acwright/6502-PRG) / [6502-CRT](https://github.com/acwright/6502-CRT) | Templates to start from — a program that loads into RAM, or a cartridge that overlays ROM |
| [bin2woz](https://github.com/acwright/bin2woz) | Binary → WozMon deposits, to paste into a machine over a serial terminal |
| [cffs](https://github.com/acwright/cffs) | Build and edit CompactFlash images from the command line — up to 256 disk banks |
| [VT-AC](https://github.com/acwright/VT-AC) | A VT terminal that could have existed but didn't — VT-100 compatible, with 256 colours and a graphics mode. Desktop, web and CLI |
| [TMS9918-EDITOR](https://github.com/acwright/TMS9918-EDITOR) | Character and screen editor for the TMS9918 VDP |

## Elsewhere

- YouTube — [@acwrightdesign](https://www.youtube.com/@acwrightdesign)
- itch.io — [acwrightdesign.itch.io](https://acwrightdesign.itch.io)
- Instagram — [@acwrightdesign](https://instagram.com/acwrightdesign)
- Pinterest — [acwrightdesign](https://pinterest.com/acwrightdesign)
- Medium — [@acwrightdesign](https://medium.com/@acwrightdesign)

## Tools of the Trade

![](https://img.shields.io/badge/Code-6502%20Assembly-informational?style=flat&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Code-C-informational?style=flat&logo=c&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Code-C++-informational?style=flat&logo=cplusplus&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Code-Swift-informational?style=flat&logo=swift&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Code-Ruby-informational?style=flat&logo=ruby&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Tools-cc65-informational?style=flat&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Tools-KiCad-informational?style=flat&logo=kicad&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/Tools-Xcode-informational?style=flat&logo=xcode&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/OS-macOS-informational?style=flat&logo=apple&logoColor=white&color=1894C1)
![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=1894C1)
