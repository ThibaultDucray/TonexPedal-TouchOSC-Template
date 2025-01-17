# The philosophy: an Amp (+ Cab) and a programmable pedalboard

After a lot of reflexion, I've established a new way of using the Tonex Pedal (incl. Tonex One).

I consider the Tonex Pedal as a standalone Amp (+ Cab) and a Pedalboard (NG, comp, mod, dly, reverb).

But one thing is missing: create, save and load the settings of the pedalboard.

Thus, I updated my previous TouchOSC template with new features, showing the Tonex Pedal parameters in 3 sections:
- section 1: the amp eq settings
- section 2: the pedalboard setings
- section 3: the presets to store and reload the pedalboard settings

See video for details: https://youtu.be/aIU2B9H2NHg

# What is TonexPedal-TouchOSC-Template?

Bothered by the impossibility of setting up the ToneX Pedal directly from ToneX software? Use this template with [TouchOSC](https://hexler.net/touchosc)!

Complete template to parameter the ToneX pedal from your computer using MIDI (standard MIDI or MIDI over USB). Switch presets, activate / deactivate effects (Reverb, Compressor, NoiseGate, Equalizer, Modulations, Delays), tune effects parameters, save the pedalboard (noise gate, compressos, modulations, delays, reverbs) in one of the 20 presets.

Also, on MIDI channel 5: load presets 1 to 20. To use: send MIDI message to TouchOSC on channel 5: CC <preset_number>

# Download

Download and install [TouchOSC from Hexler.net](https://hexler.net/touchosc).

To use on MIDI channel 2: download the [ToneX-controler-3.tosc file](https://github.com/ThibaultDucray/TonexPedal-TouchOSC-Template/blob/main/ToneX-controler-3.tosc) in the files section of this GitHub project.

To use on MIDI channel 1 (mandatory for Tonex One): download the [ToneX-controler-3-channel1.tosc file](https://github.com/ThibaultDucray/TonexPedal-TouchOSC-Template/blob/main/ToneX-controler-3-channel1.tosc) in the files section of this GitHub project.

There is also a smartphone version in the files section.

# Configuration

Set your ToneX Pedal to MIDI channel 2 (or change all messages inside message mapping view to the desired MIDI channel).

Using Tone One? Chose the "channel1" file in the files section.

# Limitation

Cannot read the settings from the Tonex Pedal (limitation of the pedal itself).
SAVE the file after use to keep the 20 presets saved in TouchOSC.

# Screenshot

![Main screen](https://raw.githubusercontent.com/ThibaultDucray/TonexPedal-TouchOSC-Template/refs/heads/main/ToneX-controler-3.jpg "Main screen")
