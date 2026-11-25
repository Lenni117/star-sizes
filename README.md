# STAR SIZES

Two mobile pages about stars, drawn to scale.

- `index.html` – **Star sizes**: 16 stars on a common scale, from KY Cygni to white dwarfs.
- `bubbles.html` – **Star bubbles**: about 131 000 stars, ranked by luminosity (brightest top-left, dimmest bottom-right), dot colour = star colour, dot size = radius, with category buttons.

Live: https://lenni117.github.io/star-sizes/ and https://lenni117.github.io/star-sizes/bubbles.html

## Licence

The pages and the data embedded in them are shared under **CC BY-SA 4.0** (`LICENSE`), because they are adapted from the
CC BY-SA 4.0 licensed HYG database. Anyone reusing them must credit the sources below, indicate changes, and share under the same licence.

The typeface **Arcon Regular** (Copyright (c) 2010 Martin Zarth, Reserved Font Name "Arcon") is embedded unmodified and stays under the
**SIL Open Font License 1.1** (`OFL-Arcon.txt`). It is not covered by CC BY-SA.

## Data sources and attribution
- **HYG database v4.1** (Hipparcos, Yale Bright Star, Gliese), https://github.com/astronexus/HYG-Database, CC BY-SA 4.0.
- **JMDC**, JMMC Measured Stellar Diameters Catalogue, Duvert (2016), via VizieR II/345.
- **IACOB** O-star spectroscopy, Holgado et al. (2018), via VizieR J/A+A/613/A65.
- **Red supergiants**: Levesque et al. (2005), ApJ 628, 973, Table 4 (radii and temperatures).
- **Yellow super- and hypergiants**: Table 1 of arXiv:2602.02449 (2026).
- **White dwarfs**: Gaia EDR3 catalogue of Gentile Fusillo et al. (2021), via VizieR J/MNRAS/508/3877 (probability of being a white dwarf above 0.75).

Licences of the catalogues other than HYG were not checked individually. Their values are published scientific data; please cite the papers.

## Changes made to the source data
- HYG: temperature computed from B-V colour (Ballesteros formula), radius computed from luminosity and temperature; stars without a real distance or usable colour removed; stars that also have a measured radius (same HD number) replaced by that entry; white dwarfs also present in the Gaia list removed.
- JMDC: angular diameter converted to radius with the HYG distance; strongly variable stars, emission-line and carbon stars removed.
- IACOB: luminosity and radius derived from HYG distance and magnitude.
- Class labels come from the catalogues' luminosity classes. For stars without one, a class was inferred from temperature and luminosity (k-nearest neighbours, kept only above 80 % agreement), and is marked as inferred on the page.
- "Hypergiant" in the two supergiant lists is a threshold set here (L at least 2x10^5 L☉ and R at least 100 R☉), not a catalogue class.
- Ages and phase durations are rough typical values and are labelled as estimates.
