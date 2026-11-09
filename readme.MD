# Omertà — Morse Code Translator & Audio Encoder/Decoder

Omertà is a modern Morse code toolkit built with a custom desktop interface for translating, playing, visualizing, and exporting Morse code. It combines real-time text↔Morse conversion, configurable audio playback, waveform generation, file workflows, and music-based encoding/decoding in a single application.

## Overview

The project is designed as a full-feature Morse code workstation rather than a basic converter. It supports both practical translation tasks and more experimental workflows such as waveform rendering and MIDI-based Morse encoding.

## Core Features

- **Real-Time Input Validation**  
  Checks input as you type to help prevent invalid Morse or text entries.

- **Text ↔ Morse Conversion**  
  Convert standard text into Morse code and decode Morse back into readable text.

- **Audio Playback**  
  Play Morse output as audio with adjustable speed and tone frequency.

- **Waveform Generation**  
  Generate Morse waveform visuals and save them as image files.

- **File Import / Export**  
  Load content from files and export translated Morse output when needed.

- **Music Encoding / Decoding**  
  Encode Morse sequences into MIDI-style musical output and decode supported musical representations back into text.

- **Modern GUI**  
  Built with CustomTkinter for a cleaner, more polished desktop experience.

## Feature Breakdown

### Translation
- text to Morse conversion
- Morse to text conversion
- live validation during input

### Audio Tools
- Morse tone playback
- adjustable playback speed
- adjustable playback frequency

### Visual Tools
- waveform creation
- waveform image export

### File Workflows
- file upload for conversion
- text export of generated Morse data

### Experimental Extensions
- MIDI/music-based Morse encoding
- music-based decoding workflows

## Installation

### Requirements
- Windows (the current `Omerta.py` imports the Windows-only `winsound` module)
- Python 3.x
- dependencies listed in `requirements.txt`

### Setup
1. Clone the repository or download the project files.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Run the main application:

```bash
python Omerta.py
```

## Dependencies

The original dependency list includes:

- `customtkinter`
- `opencv-python`
- `numpy`
- `pillow`
- `matplotlib`
- `scikit-learn`
- `scipy`
- `music21`
- `pywavelets`

## Usage

1. Start the application.
2. Enter either plain text or Morse code into the input field.
3. Convert between formats using the available controls.
4. Adjust speed and frequency for audio playback.
5. Generate waveforms or use file-based workflows as needed.
6. Explore music encoding and decoding from the side panel or advanced tools section.

## Intended Use

Omertà is intended for educational use, signal exploration, Morse code practice, and experimental audio/visual encoding workflows.

## License

This project is licensed under the MIT License.
