## Technical Details
This FM Synthesizer is designed to explore and demonstrate the principles of non-linear synthesis, specifically **Frequency Modulation (FM) synthesis**, with added functionality and visual tools for a rich user experience. 
Below are the key details about its architecture and features:

## Core Functionality

- Utilizes **FM synthesis with three operators**, allowing for intricate sound design and rich harmonic textures.
- Includes a **Low-Frequency Oscillator (LFO) in Operator 3**, which creates a tremolo effect for added modulation possibilities.

### Algorithms

- Features **4 base algorithms** that expand to 8 configurations through **feedback on Operator 1**.

- Feedback enhances harmonic complexity, providing richer timbral options.

## FM Parameters

- Designed for educational purposes, helping users visualize and understand FM synthesis fundamentals.

- Key parameters such as the carrier-to-modulator ratio (C:M) and the modulation index dynamically affect the waveform and sound.

## Real-Time Visualization:

**Waveform Display:** 

   Visualize how FM synthesis shapes the output signal in real time.

**Spectrum Analyzer:** 

   Observe the harmonic content of the sound dynamically.

**Dynamic Labels:** 

  Parameter labels adjust based on the current state, providing clear feedback to the user.

**VU Meter:** 

Monitor the output signal level to ensure balanced audio levels.

## Effects Modules:

Includes two post-synthesis effects for further sound design:

*Reverb:* Adds spatial depth and ambience.

*Delay:* Creates echo effects, enhancing rhythmic and tonal complexity.

## Preset Bank:

A built-in storage system allows users to save and load custom presets, making it easy to experiment and revisit favorite sounds.

## Development Tools:

Built with Csound for synthesis and Cabbage for UI design, providing a seamless integration of sound generation and interface usability.

## Purpose and Goals

This synthesizer is designed to be both a learning tool and a creative instrument, suitable for anyone interested in FM synthesis. Whether you're a beginner or an advanced sound designer, its educational features and flexible functionality aim to inspire and facilitate your sound design journey.
