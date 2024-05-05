# SynthCard
Another SynthCard based on **BenjiaoModular's** SynthCard standard but using Eurorack format power (±12V)

Original: https://github.com/benjiaomodular/SynthCard/blob/main/

Version 0.1 - Initial Commit
Initial version of my SynthCard. 
Features:
- LMNC Simplest Oscillator (https://www.lookmumnocomputer.com/simplest-oscillator)
- Rene Schmitz MS-20 Filter based on LMNC's Stripboard design (https://www.lookmumnocomputer.com/simple-filter)


Issues:
- Missing line (Fixed)
- Oscillator level too low
- Oscillator range is to small
- Tone knob wired in backwards
- Pitch CV IN is actually OSC OUT without Tone
- I want to make seperate input for the filter so external audio can be processed



Version 1.1 - Under development
Fixed Issues:
- Missing Line
- Lable for Pitch CV IN changed to OSC OUT (Still no tone control yet)

New Issues:
-

## Oscillator Notes
To address oscillator range is to small:
Change electrolytic capacitor value; the smaller the capacitor value the quicker it oscillates.
Suggested values:

Bass|100uf
Tenor|33uf
Alto|10uf

Credits: Paul Bergels Triple Skulls Oscillators