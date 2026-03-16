5parks VST3 Mega Serum-Style Foundation

This pass is a substantial rewrite toward a modern wavetable synth layout.

Included:
- Renamed project/product to 5parks VST3 / FiveParksVST3
- Two wavetable-style oscillators with octave/semi/fine, unison, detune, blend,
  phase, random phase, wavetable position, level and pan controls
- Sub oscillator with waveform selection and direct out mode
- Noise generator with pitch, phase, pan, level and direct out
- Multimode filter with cutoff, resonance, drive, mix and pan
- 3 envelopes and 4 LFOs
- 6-slot modulation matrix with source/destination/amount controls
- FX section with distortion, chorus, delay, reverb and compression amount
- Stereo voice engine with poly/mono/legato and glide
- Visual feedback components for waveform, LFO and modulation matrix summary
- Layout pushed closer to modern wavetable synth UI conventions

Notes:
- This is source-only and was not compiled in the container because JUCE/MSBuild is
  not available here.
- Drag-and-drop modulation is represented by a routable matrix UI and visualization,
  not full mouse-drop assignment logic yet.
- Wavetable loading/import is represented by generated wavetable scanning rather than
  file import.
