# Tritonet Brainwave

A browser-based tool that maps EEG brainwave data to musical harmony in real time. Built as a single self-contained HTML file using p5.js, it generates MIDI output for SATB voice chords driven by brainwave frequency bands (Delta, Theta, Alpha, Beta, Gamma).

## Features

- **Brainwave-to-MIDI mapping** — Delta, Theta, Low/High Alpha, Low/High Beta, Low/High Gamma bands each control separate MIDI CC values
- **SATB voice harmony** — Bass, Tenor, Alto, Soprano with configurable chord types (triad, etc.)
- **Real-time visual feedback** — p5.js canvas visualization of the harmonic state
- **MIDI channel & velocity control** — configurable channel, velocity, and note range
- **OSC support** — toggle OSC output alongside MIDI
- **Performance modes** — Position, Hold, Legato, Triton, Brain, and Filter toggles
- **Autotune & root note control** — MIDI CC buttons for live tuning adjustments
- **Zero dependencies** — everything is bundled into a single `.html` file

## Quick Start

### Try it live

Visit the [**live demo →**](https://tolgazafer.github.io/Tritonet-Web-2/Tritonet_Web_2.html) directly in your browser. No installation needed — just open and play.

### Download

1. Go to the [**Releases page**](https://github.com/tolgazafer/Tritonet-Web-2/releases) to download the latest version, **or**
2. Click **Code → Download ZIP** at the top of this page, extract, and open `Tritonet_Web_2.html` in any modern browser.

### Requirements

- A modern browser (Chrome, Firefox, Edge, Safari)
- A Web MIDI–capable browser (Chrome recommended) if you want MIDI output
- An EEG headset or MIDI source feeding brainwave CC data

## Usage

1. Open `Tritonet_Web_2.html` in Chrome
2. Allow MIDI access when prompted
3. Select your MIDI input/output channel using the **MIn ▲▼** buttons
4. Use **▲▼** buttons to change channel, voices (SATB), and harmony type
5. Toggle **Brain** to enable brainwave-driven mode, or use the MIDI CC buttons manually
6. Use **Visual** to show/hide the p5.js canvas visualization

## Controls

| Button | Description |
|--------|-------------|
| Ch ▲▼ | MIDI channel selection |
| Voices ▲▼ | Voice configuration (SATB, SAT, etc.) |
| Harmony ▲▼ | Chord type (triad, etc.) |
| Position / Hold / Legato / Triton | Performance mode toggles |
| Brain | Enable brainwave-driven mode |
| OSC | Toggle OSC output |
| Visual | Show/hide canvas visualization |
| Delta / Theta / Alpha / Beta / Gamma | Send brainwave band values as MIDI CC |
| Night / Root / Atune | Night mode, root note, autotune |

## License

MIT — free to use, modify, and distribute.
