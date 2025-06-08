# Pseudocode – DSP Audio Effects Unit

## Goal
Apply real-time audio effects (e.g., echo, reverb, low-pass) using STM32 or similar MCU.

## Flow
- [ ] Read PCM audio via I2S
- [ ] Apply effect:
  - Echo: delay line buffer
  - Reverb: multiple short delays
  - LPF: FIR filter
- [ ] Output modified audio over DAC
- [ ] Add button menu to select effects
