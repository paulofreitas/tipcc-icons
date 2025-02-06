# Changelog

## 2025-02-05

- Added BAN icons (PNG+SVG), extracted from their official press kit available at <https://banano.cc/presskit><br>
  SVG icon compressed, PNG icon resized from original 512x512 and compressed
- Added DGB icons (PNG+SVG), extracted from their official repository available at <https://github.com/DigiByte-Core/digibyte-logos><br>
  SVG icon edited and compressed, PNG icon converted from SVG and compressed
- Further compressed SVG icons using new tooling: `svgo`, Vecta Nano and `scour` (first pass with `svgo`, second pass with Vecta Nano, third pass with `svgo` again and `scour` as a last pass)
- Fixed PNG icons to use 32-bit RGB+alpha bit depth and lossless compression using new tooling: `svg2png` for SVG to PNG conversion, `magick` for PNG resizing and `zopflipng` for PNG compression

## 2025-02-04

- Added OP icons (PNG+SVG), extracted from their official brand kit available at <https://www.optimism.io/brand><br>
  SVG icon compressed, PNG icon converted from SVG and compressed
- Added NANO icons (PNG+SVG), extracted from their official currency kit available at <https://nano.org/en/currency><br>
  SVG icon compressed, PNG icon resized from original 1080x1080 and compressed

## 2025-02-03

- Added BONC icons (PNG+SVG), extracted from their [official brand kit](https://bonc.bonkscoin.io/BONCBrandKit.zip) available at <https://bonkscoin.io/><br>
  SVG icon compressed, PNG icon resized from original 512x512 and compressed
- Added TT icon (PNG), extract from their developers GitBook available at https://docs.developers.thundercore.com/<br>
  PNG icon resized from original 200x200 and compressed