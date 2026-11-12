# Doepfer Drehbank — Reason Remote Codecs

Deprecated Reason Remote files (Lua codecs + remote maps) for the Doepfer Drehbank MIDI knob controller, uploaded as-is. No longer in development; kept here as an archive.

The codecs and maps are my own work, written in 2017.

There are **two variants**, each a separate surface in Reason. Install one or both:

| Folder | Surface in Reason | Main Mixer layout |
|--------|-------------------|-------------------|
| `Sends/` | Doepfer · Drehbank FX | 128 knobs = FX1–FX8 send levels for 16 mixer channels. Also maps many Reason devices (see below). |
| `EQ/` | Doepfer · Drehbank EQ | 128 knobs = HF / HMF / LMF / LF gain and FX5–FX8 send levels for 16 mixer channels. |

Both use the same codec: 128 knobs (`Knob 1`–`Knob 128`), 8 CCs (15, 18, 21, 24, 27, 30, 40, 43) on each of MIDI channels 1–16, input only.

## Drehbank FX: other devices

Besides Reason's Main Mixer, the Sends map covers: Main Mixer Channel, Mixer 14:2, Line Mixer 6:2, Combinator, Thor, SubTractor, Malström, NN-19, NN-XT, Dr. Rex, Redrum, Kong, MClass Equalizer / Stereo Imager / Compressor / Maximizer, RV7000, Scream 4, BV512, RV-7, DDL-1, D-11, ECF-42, CF-101, PH-90, UN-16, COMP-01, PEQ-2, RPG-8, ReGroove Mixer, ID8, Line 6 Guitar Amp / Bass Amp, Neptune, Alligator, Pulveriser, The Echo and Radical Piano. It also has scopes for Record and Reason Essentials.

## Install

1. Copy the `.luacodec`, `.lua` and `.png` files of the variant(s) you want to the `Remote/Codecs/Lua Codecs/Doepfer/` folder.
2. Copy the matching `.remotemap` file(s) to the `Remote/Maps/Doepfer/` folder.
3. Restart Reason, then add the surface manually in Preferences → Control Surfaces (Manufacturer: Doepfer, Model: Drehbank FX or Drehbank EQ).

On macOS the Remote folder is `~/Library/Application Support/Propellerhead Software/Remote/`; on Windows it's `%APPDATA%\Propellerhead Software\Remote\`.

## Licence

MIT — see `LICENSE`.
