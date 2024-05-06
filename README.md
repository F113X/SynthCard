# SynthCard
Another SynthCard based on **BenjiaoModular's** SynthCard standard but using Eurorack format power (±12V)

![SynthCard](Images/synthcard-dimensions.png)

Original: https://github.com/benjiaomodular/SynthCard/blob/main/

Version 0.1 - Initial Commit

Initial version of my SynthCard. 

Features:
- LMNC Simplest Oscillator with tone control (https://www.lookmumnocomputer.com/simplest-oscillator)

![Synthcard](Images/SUPER+SIMPLE+OSCILLATOR.png)
![Synthcard](Images/SIMPLE+OSCILLATOR+SCHEMATIC.jpeg)

- Rene Schmitz MS-20 Filter based on LMNC's Stripboard design (https://www.lookmumnocomputer.com/simple-filter)

![SynthCard](Images/MS20-Stripboard.jpeg)

Issues:
- Missing line (Fixed)
- Oscillator level too low
- Oscillator range is to small
- Tone knob wired in backwards (Fixed)
- Pitch CV IN is actually OSC OUT without Tone
- I want to make seperate input for the filter so external audio can be processed



Version 1.1 - Under development

Fixed Issues:
- Missing Line
- Tone is wired in correctly
- Lable for Pitch CV IN changed to OSC OUT (Still no tone control yet)

New Issues:
- Not tested yet

## Oscillator Notes
To address oscillator range is to small:

Change electrolytic capacitor value; the smaller the capacitor value the quicker it oscillates.
Suggested values:

- Bass 100uf
- Tenor 33uf
- Alto 10uf

Credits: Paul Bergels Triple Skulls Oscillators