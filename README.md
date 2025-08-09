# TTY Art AFSK Generator

**Author:** Frankie Caswell  
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

## Overview

The **TTY Art AFSK Generator** is a browser-based tool for converting images or text into ASCII art, then encoding it into **Baudot/ITA2 RTTY** as AFSK audio.  
It was designed for **educational and testing purposes** — to demonstrate how images and text can be transformed into formats compatible with vintage teletypes (e.g., Model 28) and other narrowband digital communication systems.

This tool runs entirely in the browser — no installation required — making it ideal for classroom demonstrations, hobby experiments, and preservation of historic communication methods.

---

## Features

- **Image to ASCII conversion** with adjustable:
  - Character set
  - Brightness and contrast
  - Vertical scale / aspect ratio
  - Threshold (binary black & white) mode
  - Inversion toggle
- **Text to RTTY/AFSK** conversion:
  - Configurable baud rate, mark/space frequencies, and stop bits
  - Mechanical shift delay simulation for FIGS/LTRS
  - Optional mark/space inversion
- Generates **AFSK WAV** audio directly in the browser for playback or saving
- Compatible with standard **ITA2 (Baudot)** character set

---

## Educational Use

This project was created for:
- Teaching basic digital communications concepts
- Demonstrating ASCII and Baudot encoding
- Showing real-time modulation into AFSK audio
- Understanding mark/space frequency shifts in RTTY
- Experimenting with image-to-text conversion for constrained output devices

It is **not intended** for production or mission-critical communications.

---

## Live Demo

https://unluckyfett.github.io/TTY-ART-GENERATOR/

---

## License

This work is licensed under a  
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).  
You are free to share and adapt the material for any purpose, even commercially, **as long as appropriate credit is given**.

---

## Acknowledgments

- Inspired by the preservation of historic teleprinter communications
- Uses standard HTML5 Canvas, JavaScript, and Web Audio API — no external dependencies
