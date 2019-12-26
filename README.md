# Traktor S5 Mod

This is my attempt to fix all the shortcomings of this near-perfect DJ controller.

Please reach out to me with any bugs or feature requests.

## Compatibility

Traktor Pro:
- 2.11.0
- 3.2.19

NOTE: Traktor Pro 2 is no longer supported and may not contain all features listed below.

## Modifications

**Display:**

- Spectrum colors to distinguish highs, mids, and lows
- Deck header shows
  - color-coded Camelot key (when key is LOCKED)
  - approximate Camelot key (when key is UNLOCKED)
- Browser SortBy reduced to three variables: artist, bpm, and key
- Removed overlay hide delays

**Controller:**

- Use left deck knob to skip through song (by loop size)
- Default course adjustment for:
  - global and deck tempo knobs
  - beatmatch edit offset knob
- Touchpad scratches by default
  - hold SHIFT to nudge
- Hold back (<) in deck view to reset key
- SHIFT + FLUX for flux reverse

## Installation

**Windows:**

1. Download or clone the repository.
2. Depending on your Traktor Pro version, copy the corresponding qml folder to:
   `C:\Program Files\Native Instruments\Traktor 2\Resources64`
   or
   `C:\Program Files\Native Instruments\Traktor Pro 3\Resources64`
   and replace all files.

**Mac:**

1. Download or clone the repository.
2. Depending on your Traktor Pro version, navigate to:
   `Applications/Native Instruments/Traktor 2`
   or
   `Applications/Native Instruments/Traktor Pro 3`.
3. Right click on Traktor and select `Show Package Contents`.
4. Copy the qml folder to `Contents/Resources` and select merge. (Note: Merge preserves newer items. Make sure to download this mod AFTER installing or updating Traktor.)

## Screenshots

![Colored Camelot key](images/color_key.jpg)
![Approximate Camelot key](images/approx_key.jpg)
