# Bit-Clip Lab data: Banjo-Tooie · N64 NTSC (USA)

Data files for the [Bit-Clip Lab](https://kweber1.github.io/bitclip-lab/tooie/?v=ntsc) viewer (the viewer and the tools that make these files are in [kweber1/bitclip-lab](https://github.com/kweber1/bitclip-lab)). Each game version has its own repository so each gets its own 1 GB GitHub Pages site; the viewer loads from all of them on the same `kweber1.github.io` address.

Exhaustive bit-clip census of every Banjo-Tooie level: `data/room-<map>.gz.wasm` (gzipped JSON: collision mesh, game-look mesh, seams, and one spot per 0.25-unit cell with the count of every crack float in it per outcome), `data/index.json` (level list and totals), `data/objects.gz.wasm` (objects and enemies per map, from a BizHawk dump).

Files end in `.wasm` so GitHub Pages serves the gzipped bytes as they are. No game art is published here.
