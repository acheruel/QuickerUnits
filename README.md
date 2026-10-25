# QuickerUnits

Unit converter built for civil and structural engineering, in English and French.

**Version 0.6.5 · Anthony Chéruel · 2026-10-25**

**Live app:** https://acheruel.github.io/QuickerUnits/

## Concept

A single dependency-free HTML file.

## Features

- 7 main columns: length, force, line load, moment, pressure/stress, area, mass.
- 9 extra columns: volume, density (per volume, area, length), moment of inertia I, section modulus S, stiffness K, speed, acceleration, temperature, land area. I and S include CISC units.
- Quick convert bar (press `/`): type `25 ksi to MPa`, `5'-6 1/2" to mm` or `100 °C to °F`.
- Feet-inches as decimals or in drawing notation (`1′-11⅝″`, nearest 1/16″); both can be typed.
- Every box is editable and everything converts live.
- SI units first, then imperial, with a clear divider.
- Consistent significant figures, also in the conversion factors under each box; French notation in French mode.
- Clickable table of common equivalences.
- Expressions accepted (`2*600`, `1.5e3`), keyboard navigation, one-click copy.

## Usage

The live link always serves the latest version; open pages show an update banner.

Factors are exact (1959 international definitions, NIST SP 811; g = 9.80665 m/s²).
