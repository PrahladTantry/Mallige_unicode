# Mallige Unicode

A modern Unicode-compliant font for the **Tulu Script (Unicode 16.0)** designed for high-quality digital typography, publishing, education, and software applications.

Mallige Unicode aims to provide a complete implementation of the newly encoded Tulu script while maintaining readability, traditional aesthetics, and robust OpenType shaping.

---

## Features

### ✓ Unicode 16.0 Support

Implements the official Unicode encoding for the Tulu script.

Supported Unicode Block:

```
U+11380 – U+113D8
```

The font follows the Unicode character repertoire for Tulu and is intended to work with modern rendering engines.

---

### ✓ Complete Tulu Script Coverage

Includes support for:

- Independent vowels
- Consonants
- Dependent vowel signs
- Virama
- Combining signs
- Numerals (where applicable)
- Punctuation
- Newly encoded characters

---

### ✓ Smart OpenType Layout

Mallige Unicode uses OpenType shaping to automatically construct correct Tulu orthography.

Implemented GSUB features include:

- `akhn` — Akhand ligatures
- `blwf` — Below-base substitutions
- `liga` — Standard ligatures
- `rphf` — Repha forms

These substitutions ensure that conjuncts and special character sequences render correctly without requiring manual glyph selection.

---

### ✓ Advanced Mark Positioning

Implemented GPOS features include:

- `mark` — Accurate positioning of combining marks
- `kern` — Kerning support

These improve readability and produce aesthetically balanced text.

---

### ✓ Unicode Shaping Engine Compatible

Designed to work with modern shaping engines including:

- HarfBuzz
- Uniscribe
- CoreText
- DirectWrite

Applications using these engines should automatically display correct conjunct formation and mark positioning.

---

### ✓ High Glyph Count

Current version contains

**1853 glyphs**

allowing extensive OpenType substitutions and positioning beyond the raw Unicode character count.

---

## Technical Information

| Property | Value |
|-----------|-------|
| Font Name | Mallige Unicode |
| Style | Regular |
| Version | 1.000 |
| Glyphs | 1853 |
| Unicode Characters | 177 |
| OpenType Layout | GSUB + GPOS |
| Digital Signature | Included |

---

## OpenType Features

| Feature | Description |
|----------|-------------|
| akhn | Akhand ligatures |
| blwf | Below-base substitutions |
| liga | Standard ligatures |
| rphf | Repha handling |
| mark | Combining mark positioning |
| kern | Kerning |

---

## Intended Applications

Mallige Unicode is suitable for

- Books
- Dictionaries
- Academic publications
- Government documents
- Educational material
- Websites
- Mobile applications
- Desktop publishing
- Research on Tulu language and script
- Unicode software development

---

## Installation

### Windows

1. Download the font.
2. Right-click the font file.
3. Select **Install** or **Install for all users**.

### Linux

Copy the font into

```
~/.local/share/fonts/
```

then run

```
fc-cache -fv
```

### macOS

Double-click the font and choose **Install Font**.

---

## Recommended Applications

Mallige Unicode works well with

- LibreOffice
- Microsoft Word
- Adobe InDesign
- Adobe Illustrator
- XeLaTeX
- LuaLaTeX
- Scribus
- Affinity Publisher
- Inkscape
- Modern web browsers

---

## Rendering Requirements

Correct rendering requires an application with OpenType shaping support.

Applications using HarfBuzz or equivalent shaping engines will automatically perform:

- conjunct formation
- mark positioning
- ligature substitution
- vowel reordering
- contextual shaping

---

## License

See the accompanying LICENSE file.

---

## Author

**Prahlad Prasad Tantry**

---

## Acknowledgements

Special thanks to everyone working towards the digitization and preservation of the Tulu script and its Unicode implementation.

---

## Version History

### Version 1.000

- Initial public Unicode release
- Unicode 16.0 Tulu support
- OpenType GSUB implementation
- OpenType GPOS implementation
- Smart ligature support
- Advanced mark positioning

---

## Repository Structure

```
Mallige-Unicode/
│
├── Mallige_Unicode.ttf
├── LICENSE
├── README.md
└── specimens/
```

---

## Contributing

Bug reports, rendering issues, OpenType improvements, and suggestions are welcome through GitHub Issues.

---

## Citation

If you use Mallige Unicode in academic work, publications, or software projects, kindly cite this repository.

---

## Project Goals

Mallige Unicode seeks to provide

- complete Unicode compliance
- high typographic quality
- robust OpenType behavior
- compatibility across modern operating systems
- a reliable foundation for digital Tulu publishing
