# Turntable Cartridge Comparison Guide

A free, open-source comparison tool for vinyl enthusiasts to explore and compare turntable cartridges.

## Features

- **100+ cartridges** from major brands: Audio-Technica, Ortofon, Grado, Sumiko, Nagaoka, Goldring, Rega, Denon, Shure, Dynavector, Hana
- **Search** by cartridge name
- **Filter** by cartridge type (MM/MC) and compliance (low/medium/high)
- **Sort** by name, price, or sound quality
- **Discontinued models** marked and sorted to bottom
- **Sound quality ratings** (1-10 scale)
- **Compliance data** based on manufacturer specifications
- **Type classification** (MM = Moving Magnet, MC = Moving Coil)

## Usage

Simply open `index.html` in any modern web browser. No server required.

```bash
# Open directly in browser
open index.html

# Or serve locally
npx serve .
```

## Data Source

Data is sourced from audiophile reviews and manufacturer specifications. Prices are approximate and may vary by region and retailer.

## Contributing

To add or update cartridges:
1. Edit `cartridges.js`
2. Add cartridges with: id, name, soundProfile, soundQuality, compliance, price, type
3. Optionally mark discontinued: `"discontinued": true`

## License

MIT License - Feel free to use and modify.
