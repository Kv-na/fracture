# _fracture_

### an accessible, diy hardware glitcher for analog video.

## description

`_fracture_` is a straightforward, low-component-count circuit designed to violently manipulate composite video signals. 

built for the diy community, it uses a high-speed video op-amp pushed into a state of instability via a passive network of capacitors and potentiometers. the result is unpredictable geometric tearing, heavy horizontal displacement, and intense chroma blowouts. it's an affordable, hands-on way to turn clean video feeds into chaotic textures without needing expensive, hard-to-find studio gear.

due to the raw, unbuffered nature of these analog glitches, the output is best viewed directly on a crt television. 

## hardware features

* **native type-c power:** built around modern power standards. it uses a raw, unbuffered 5v supply negotiated directly from a usb type-c port via 5.1k pull-down resistors, keeping the build cheap and simple.
* **high-speed core:** designed to take advantage of the tight 5v headroom on fast op-amps (like the ad812) to generate sharp, aggressive artifacts from an analog source.
* **modular routing:** dual input/output routing switches allow you to feed the video signal forward or backward through the distortion path, multiplying the available textures with minimal extra parts.

## basic operation

1. **power:** plug a standard 5v usb type-c cable into the board.
2. **video in:** connect a composite video source (cctv camera, vcr, media player) to the IN rca jack.
3. **video out:** connect the OUT rca jack to a crt display.
4. **glitch:** start with all knobs turned counter-clockwise and switches UP. slowly bring the knobs up and flip the capacitor switches to explore different frequencies of signal failure.

---

## documentation & open-source hardware

this project is fully _open-source hardware_. all design files, schematics, and gerbers required to build, study, or modify this circuit yourself are included in this repository. 

**license & lineage**
`_fracture_` is licensed under **CC BY-SA 4.0**. 
the core architecture of this board is derived from the `_rupture_` video processor designed by [cyberboy666](https://github.com/cyberboy666/_rupture_), which itself is an adaptation of an original circuit by [karl klomp](https://www.karlklomp.nl/).
