# Fablabs Lick Detector

Inspired by the Allen Institutes: https://github.com/AllenNeuralDynamics/harp.device.lickety-split

## Introction
Goals:
- Reliable lick detection
- Low noise
- Simple adjustments and debugging
- Easy to source components
- Fast to manufacture
- Cheap to purchase

The board was designed to be soldered directly to the lick port.

Power and output TTL signal from 3-pin 2.54mm pitch pin headers.

compact footprint: 25mm x 45mm

Cost: <£10 per board

## How to Use
Solder lick spout directly to board for solid electrical connection

Input power (3.3V to 5V).

Adjust oscillator with potentiomete: put the gain to its highest, slowly reduce the gain to achieve lower THD. If the gain is too low, no sine will output.

Adjust schmitt trigger with potentiometer (the no-lick voltage on 'amp' should be about 2.7V)

## Testing and Debugging
Is VCC on?

Measure Voltage 'V+' and 'V-', are they withing +/- 1%?

Use an oscilliscope to analyse the oscillator output at 'osc'

Analyse the output on the buffer


## Test Results
### Oscillator Performance

Frequency

Amplitude

THD

Temperature Variation


### RMS-to-DC Performance

Response Time

Output Ripple

### Schmitt Trigger


## Recommended Operating Conditions

