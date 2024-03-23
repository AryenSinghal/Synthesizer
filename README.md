# Simple Synthesizer with ADSR

This Python program allows you to generate sounds with various waveforms (sine, square) and control their ADSR envelope (Attack, Decay, Sustain, Release). It also features low-pass and high-pass filters for further sound shaping.

## Requirements:

- Python 3 ([https://www.python.org/downloads/](https://www.python.org/downloads/))
- sounddevice library (`pip install sounddevice`)
- SciPy library (`pip install scipy`)
- tkinter library (included in Python standard library)

## Running the application:

1. **Install dependencies:** Open a terminal or command prompt and run:

   ```bash
   pip install sounddevice scipy
   ```

2. **Run the script:** Navigate to the directory where you saved the Python script (e.g., `synth.py`) and run:

   ```bash
   python synth.py
   ```

## Using the Synthesizer:

- The GUI window will display:
  - Frequency entry: Enter the desired frequency of the sound in Hz.
  - Duration entry: Enter the desired duration of the sound in seconds.
  - Waveform buttons: Select the desired waveform (sine, square).
  - ADSR sliders: 
    - Attack: Controls how quickly the sound reaches its peak volume.
    - Decay: Controls how quickly the sound fades out after reaching its peak.
    - Sustain Level: Sets the volume level during the sustain phase.
    - Release: Controls how quickly the sound fades out completely.
  - Filter selection: Choose between "no filter," "low pass," or "high pass" filtering.
  - Cutoff frequency entry: Set the cutoff frequency for the selected filter (in Hz).
- Click a waveform button to generate a sound with the specified frequency, duration, and ADSR envelope.

## Further Customization:

- You can modify the code within the script (e.g., `synth.py`) to adjust default values or functionalities.

## Note:

- Ensure your speakers or headphones are connected and sound output is enabled on your system.
