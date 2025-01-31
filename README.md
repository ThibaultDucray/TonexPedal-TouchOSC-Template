# The philosophy: an Amp (+ Cab) and a programmable pedalboard

After a lot of reflexion, I've established a new way of using the Tonex Pedal.

I consider the Tonex Pedal as a standalone Amp (+ Cab) and a Pedalboard (NG, comp, mod, dly, reverb).

But one thing is missing: create, save and load the settings of the pedalboard.

Thus, I updated my previous TouchOSC template with new features, showing the Tonex Pedal parameters in 3 sections:
- section 1: the amp eq settings
- section 2: the pedalboard setings
- section 3: the presets to store and reload the pedalboard settings

See video (of an old version but still understandable) for details: https://youtu.be/aIU2B9H2NHg

See documentation for details in the [Wiki section](https://github.com/ThibaultDucray/TonexPedal-TouchOSC-Template/wiki)

# What is TonexPedal-TouchOSC-Template?

Bothered by the impossibility of setting up the ToneX Pedal directly from ToneX software? Use this template with [TouchOSC](https://hexler.net/touchosc)!

Complete template to parameter the ToneX pedal from your computer using MIDI (standard MIDI or MIDI over USB). Switch presets, activate / deactivate effects (Reverb, Compressor, NoiseGate, Equalizer, Modulations, Delays), tune effects parameters, save the pedalboard (noise gate, compressos, modulations, delays, reverbs) in one of the 20 presets.

# Download

Download and install [TouchOSC from Hexler.net](https://hexler.net/touchosc).

Download the [TouchOSC .tosc file from the release section](https://github.com/ThibaultDucray/TonexPedal-TouchOSC-Template/releases).

There is also a smartphone version.

# Configuration and usage

1. Set your ToneX Pedal to the desired MIDI channel.
2. Open the layout with TouchOSC then run it by toggling Editor mode (Ctr-E on the keyboard or Right arrow icon).
3. Select the MIDI channel according to your settings in the Tonex Pedal.
4. Configure your settings live, save the params into the Presets section.

# Documentation

See the [Wiki section](https://github.com/ThibaultDucray/TonexPedal-TouchOSC-Template/wiki)

# Limitations

- Cannot read the settings from the Tonex Pedal (limitation of the pedal itself).
- Doesn't save the Pedalboard presets in the ToneX Pedal: it saves them in the layout.
- SAVE the file after use to keep the 20 presets saved by TouchOSC.

# Screenshots

![Main screen](https://raw.githubusercontent.com/ThibaultDucray/TonexPedal-TouchOSC-Template/refs/heads/main/ToneX-controler-4-3.png "Main screen")

![Smartphone screen](https://raw.githubusercontent.com/ThibaultDucray/TonexPedal-TouchOSC-Template/refs/heads/main/ToneX-controler-4-smartphone.png "Smartphone screen")

# Changelog

- version 4.3: Added feature for automatic loading of presets and automatic sending of pedalboard settings when changing patch on ToneX Pedal
- version 4.2: Added preset naming feature, and a simpler browser for presets.
- Version 4: Added MIDI channel selector
- Version 3: Added Presets features, for Pedalboard section (comp, mod, delay, reverb, NG) save and load 20 presets directly into TouchOSC.
- Version 2: Support for effects (comp, mod, delay, new reverbs) after Nov. 2024 update.
- Version 1: Initial layout, it does not fit to ToneX Pedal since Nov. 2024 firmware update.

# Wanna say thank you?

Listen to our music! https://walruspark.co/

# More infos

More infos, apps and projects: https://tducray.fr
