# CS-128-H-Final-Project

**Group Name:** emul-guys  
**Group Members:**
- Adarsh Krishnan (adarshk5)
- Hyunwoo Kim (hyunwoo7)

## Project Introduction
We intend to implement a fully functioning NES emulator in Rust. Both of us are new to video game emulation, but there already exist several resources for building an NES emulator, so this should be possible to complete in the time provided. 

## Technical Overview
To emulate the NES, it is necessary to emulate the Central Processing Unit (CPU), the Picture Processing Unit (PPU), their access to Random Access Memory (RAM), and the Audio Processing Unit (APU). In addition, it is necessary to emulate the inputs of the gamepad as well as the data accessed from reading game cartridges. We intend to complete implementation of the CPU, its access to RAM, and cartridge reading by **Checkpoint 1** and implementation of the PPU, its access to RAM, and joypads by **Checkpoint 2**.

## Possible Challenges
Some challenges we anticipate are efficiently managing program operations as a less than optimal implementation will result in frame rate drops and audio glitches. In addition, working close to the hardware level (at least virtually) is new to us as we are mainly experienced with higher-level software. 

## References
- https://bugzmanov.github.io/nes_ebook
- https://ltriant.github.io/2019/11/22/nes-emulator.html
- https://www.nesdev.org/wiki/Nesdev_Wiki
