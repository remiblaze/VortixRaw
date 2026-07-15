# Vortix Raw — one-knob granular vortex

![Vortix Raw](https://raw.githubusercontent.com/RemiBlaze/VortixRaw/main/vortixraw-ui-screenshot.png)

**One knob. Turn it up and your live signal swirls into a tempo-synced granular vortex.**

Vortix Raw is the free, one-knob edition of Vortix, Remi Blaze's hex granular sequencer. Drop it on a channel and ride the vortex — clean at zero, then vintage, then full glitch as you open it up. No MIDI, no menus, no sample loading.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install
1. Go to the [latest release](https://github.com/RemiBlaze/VortixRaw/releases/latest).
2. Download **`VortixRaw_Installer.pkg`**.
3. Double-click it and follow the installer. Signed & notarized by Apple — installs cleanly, no security warnings.
4. Restart your DAW and rescan plug-ins.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
- **SWIRL** — the one macro knob. It runs an always-on, tempo-synced hex granular engine on your live input. It's front-loaded and level-matched: at zero you get a clean, near-dry passthrough, and as you turn it up the sound moves from pristine, through warm vintage-tape character, into full glitch. The signature hex path and groove are locked in, and the engine free-runs on its own internal clock so it stays alive even with the transport stopped.

Under the hood it's a grain-degradation ("Age") engine: a rolling-off low-pass, wow & flutter, tape hiss, stereo-width narrowing, and bit / sample-rate reduction at the top of the sweep, followed by soft-knee saturation and a DC blocker. Pure audio insert — no MIDI. Reports zero latency, constant across the whole knob sweep.

---

## 💻 System Requirements
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host (your DAW of choice)

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/VortixRaw/issues)** tab with your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
