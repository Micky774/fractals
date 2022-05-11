# fractals

## Atlas
- V2: Process again w/ contrast norm --> log(t+1)

### glow
- Trap: |xx - 0.5 + yy - 0.5|
- Processing: t --> log(t + 1)
- CMAP: "inferno_r"

### crown
- Trap: |((x+0.75)\*\*2) + ((y-0)\*\*2) - .5|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### warble
- Trap: |((x+0.75)\*\*2)\*1.5 + ((y-0)\*\*2)\*4 - 1|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### centipede
- Trap: |((x+0.75)\*\*3)\*1.5 + ((y-0)\*\*2)\*4 - 1|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### trajectory
- Trap: |x|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"