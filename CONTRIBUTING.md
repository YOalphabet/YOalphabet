# Contributing to YOalphabet

Thank you for your interest. YOalphabet is a small, finished script, and it grows through experiments, forks and examples. Contributions are welcome.

## Ways to help

- **Voice recordings.** The 16 base sounds are `o a e t u n l v i b s h p m k j` (IPA, in glyph order 0-15). Original recordings are wanted for the clicker and for readers.
- **Styles and fonts.** Rounded, handwritten, calligraphic, pixel, dot-matrix and tactile variants.
- **Examples.** Real texts written in YOalphabet, posters, cards, games, puzzles.
- **Translations.** README and spec translated into other languages.
- **Readability tests.** Reports on confusion between glyphs, learning time, handwriting trials.
- **Tools.** Converters, keyboard layouts, font packaging, ports of the clicker.
- **Bug reports.** Anything that does not match the specification.

## How to contribute

1. Open an issue to discuss an idea, or send a pull request directly.
2. For sounds and images, attach the file and state the author and license.
3. Keep changes small and focused: one idea per pull request.

You can also reach the author on X: https://x.com/YOalphabet

## What must stay stable

The construction rules of the 16 glyphs are fixed: four edge bits (right, bottom, left, top), the internal diagonals, and the IPA value of each glyph. A new style may soften or restyle glyphs, but each glyph must keep its identity: the main contour, the diagonal placement and the line density.

YOconlang is experimental and separate from YOalphabet. Proposals for it are welcome, but its categories may change.

## Sound recordings

Recordings must be your own work, with no third-party material.

- **License:** CC0 or CC BY (so they can be used freely in the clicker and the repository).
- **Format:** mono, 44.1 kHz, about 0.6 s, one sound per file, no noise, no leading silence.
- **File names:** by glyph, for example `a.ogg`, `e.ogg`. OGG and MP3 preferred.
- **Voice:** say who recorded it (a name or nickname is enough). Several voices per sound are fine.

## Licensing

Code and glyph designs are contributed under the MIT License, the same as the project. Sounds and other media follow the license stated with each file. By contributing you confirm that the work is yours and that you have the right to share it under the stated license.
