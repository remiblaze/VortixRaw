# Vortix Raw: one-knob granular vortex

![Vortix Raw free one-knob granular vortex UI](https://raw.githubusercontent.com/RemiBlaze/VortixRaw/main/vortixraw-ui-screenshot.png)

**One knob. Turn it up and your live signal swirls into a tempo-synced granular vortex.**

Vortix Raw is the free, one-knob edition of Vortix, Remi Blaze's hex granular sequencer. Drop it on a channel and ride the vortex, clean at zero, then vintage, then full glitch as you open it up. No MIDI, no menus, no sample loading.

**macOS** (Apple Silicon and Intel): AU, VST3, CLAP, AAX, Standalone. Signed and notarized by Apple.

**Windows** 10 and 11, 64-bit: VST3, CLAP, Standalone. Authenticode signed.

AAX ships on macOS only.

---

## 🚀 Download & Install

Go to the [latest release](https://github.com/RemiBlaze/VortixRaw/releases/latest) and pick your platform.

**macOS**
1. Download **`VortixRaw_Installer.pkg`**.
2. Double-click it and follow the installer. It is signed and notarized by Apple, so it installs cleanly with no security warnings.
3. Restart your DAW and rescan plug-ins. Vortix Raw appears under **Remi Blaze**.

**Windows 10 and 11, 64-bit**
1. Download **`VortixRaw_Installer.exe`**.
2. Run it and follow the installer. It is Authenticode signed.
3. Restart your DAW and rescan plug-ins. Vortix Raw appears under **Remi Blaze**.

No dongle and no extra account on either platform.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
- **SWIRL**: the one macro knob. It runs an always-on, tempo-synced hex granular engine on your live input. It's front-loaded and level-matched: at zero you get a clean, near-dry passthrough, and as you turn it up the sound moves from pristine, through warm vintage-tape character, into full glitch. The signature hex path and groove are locked in, and the engine free-runs on its own internal clock so it stays alive even with the transport stopped.

Under the hood it's a grain-degradation ("Age") engine: a rolling-off low-pass, wow & flutter, tape hiss, stereo-width narrowing, and bit / sample-rate reduction at the top of the sweep, followed by soft-knee saturation and a DC blocker. Pure audio insert, no MIDI. Reports zero latency, constant across the whole knob sweep.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/VortixRaw/issues)** tab with your macOS or Windows version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Plugin page:** [remiblaze.com/plugins/vortix-raw/](https://remiblaze.com/plugins/vortix-raw/).
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.
