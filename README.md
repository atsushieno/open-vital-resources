# open-vital-resources

It is a repository that provides various Vital resources (presets, wavetables, and LFOs), initiated by @atsushieno.
The primary aim here is to provide various resources for open-source variants of Vital ([Vitalium](https://github.com/DISTRHO/DISTRHO-Ports/tree/master/ports/vitalium), [Vitaloid](https://github.com/atsushieno/aap-juce-vital), etc.).

It is NOT going to be a repository that I am going to stock my creative sound works (I *might* do so, but not primarily). Instead, it will store some automatically converted free/open resources, often helped by [`batch-import-wavetables` branch](https://github.com/atsushieno/vital/tree/batch-import-wavetables) of my vital fork.

## Directory structures

Since it is not a good idea to mix various imported materials under one single resource directory, I split top level directories for each imported resource set. For example:

- KimuraTaroFreeWavetables
  - Wavetables
    - abs
      - abs1.vitaltable
      - abs2.vitaltable
      - (...)
    - (...)
 
Thus, when you copy the resources under Vital local condig directory (e.g. `~/.local/share/vital`), you would like to copy each top directory there, instead of its `User` directory, so that your "User" folder contents do not get overwhelmed.


## Notes

Wavetables go beyond 2048 frames. Do not forget to assign an LFO like "Saw Up" to Wavetable Key Frame.

## Current imports and licenses

All my private vital resources are distributed under the CC0 Public Domain license.

Other resources (this README.md etc.) created (not converted) by myself are distributed under CC-BY 4.0 license.

For the imported materials:

- Kimura Taro Free Wavetables https://www.kimurataro.com/free-wavetables.html - distributed under the CC0 Public Domain dedication.
- WAVEEDIT ONLINE https://waveeditonline.com - resources are distributed under the CC0 Public Domain dedication.
