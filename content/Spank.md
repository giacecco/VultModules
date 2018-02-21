+++
title = "Spank"
date = "2017-10-28T22:37:03+03:00"
layout = "module"
image ="../images/Spank.png"
+++

Spank is the envelope generator in charge of producing the snappy sounds of Trummor and Trummor 2. All transitions are exponential since they are modeled after the behavior of an analog envelope. The module includes a VCA so you can use it directly to control an input source.

## Documentation

Each of the knobs provides an attenuverter and a CV input to modulate them.

- **Attack (Knob)**: rising rate of the envelope.
- **Hold (Knob)**: time that the envelope stays in the maximum output (10 V).
- **Decay (Knob)**: rate at which the envelope returns 0 V output.
- **Mode (Switch)**:
   - **Soft**: provides longer transitions times and less snappy envelope.
   - **Hard**: faster transition times and more snappy envelope.
   - **Loop**: special mode for making snare-like sounds. Attack defines the rising and decaying time of each repetition, Hold defines the time that the envelope will repeat and Decay the final decaying time.
- **VCA(Section)**: it's an integrated VCA where the input is multiplied by the envelope.
- **Gate(Input)**: a signal larger than 2 V will trigger the envelope. 
- **Out(Output)**: actual output of the envelope signal.


