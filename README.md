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

### resonance
- Trap: |xx+yy-1/9|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### echos
- Trap: |x+yy-1|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### shattered reflections
- Trap: |(x+.75)**3+x+yy-1|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### bubbles 1
- Trap: |cos(x)+sin(y)-1|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"

### lattice
- Trap: |cos(x)+sin(y)|
- Processing: t --> log(t + 0.0025)
- CMAP: "plasma_r"
